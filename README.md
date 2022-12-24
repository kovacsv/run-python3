# run-python3

The name of the Python 3 executable is `python` on Windows, but `python3` everywhere else (don't ask). This makes it a hell to use Python 3 in `package.json` scripts. This package introduces the `run-python3` command that runs the correct Python 3 executable on all platforms.

## How to use?

Install the package.

```
npm install run-python3
```

Use it in `package.json` scripts:

```
...
"scripts": {
    "command": "run-python3 my_cool_python_script.py"
},
...
```
