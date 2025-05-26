# agentic-patterns

The goal is to show some robust agentic patterns in this repo. Robust implies:
- basic checks against hallucinations
- guard rails (to be added soon)
- self learning (to be added soon)


By employing robust agentic architecture, the accuracy of the results can be improved over one shot approach against a LLM. This `one` of the key things which makes the agentic architecture practical.


|Notebook|Tested with Model|Notes|
|---|---|---|
|agentic-pattern-base|llama3.2:3b-instruct-fp16, qwen3:32b|The initial notebook has been done with openaisdk. But subsquent notebooks and source will be done with LlamaStack.


## Getting started
### Clone the repo
### Create venv

## To get started
- Use python 3.12 or more
- download this repo and cd to it
- create a `.env` file if you want to use openai models. Paste the contents of `env-sample` and add your openai-api-key value .

- create a venv
    ```
    python -m venv .apattern
    source .apattern/bin/activate
    ```

- install the libraries
    ```
    pip install -r requirements.txt
    ```

- start the notebook with the venv
    ```
    python -m ipykernel install --user --name=.apattern
    jupyter notebook
    ```

## Model

There is nothing in this exercise the prohibits you from running against OpenAI models.  But this is also a good time to start to run models locally and test.

### ollama
- install [ollama](https://ollama.com/) locally
- run your model using ollama. For example -
    ```
    ollama run llama3.2:3b-instruct-fp16
    ```


