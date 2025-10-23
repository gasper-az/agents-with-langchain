# Agents with LangChain and LangGraph

Notes and code samples from [LangChain- Develop AI Agents with LangChain & LangGraph](https://www.udemy.com/course/langchain/?couponCode=MT251022G1) Udemy course by Eden Marco.

## How-to configure

Virtual-env for windows - [Source](https://mothergeo-py.readthedocs.io/en/latest/development/how-to/venv-win.html)

Run the next commands:

1. `python3 -m pip install virtualenv`
1. `python3 -m virtualenv venv`
    1. *Note*: Don't forget to add the `env` folder into the `.gitignore` file.
1. `.\venv\Scripts\activate`
1. `poetry env use .\venv\Scripts\python3.exe`
1. `poetry install --no-root`
1. `Invoke-Expression (poetry env activate)`
1. `poetry run python3 -m ipykernel install --user --name=agents-with-langchain --display-name "Agents with LangChain"`

To run scripts:

1. `poetry run python3 .\main.py`
