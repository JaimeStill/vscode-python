# VS Code Python Setup

Notes and examples from running through the [VS Code Python Guide](https://code.visualstudio.com/docs/python/python-tutorial).

## Restore Virtual Environment + Dependencies

1. Create the virtual environment:

    ```py
    py -3 -m venv .venv
    .venv\scripts\activate
    ```

2. Install dependencies:

    ```py
    pip install -r requirements.txt
    ```