# week_6

## Virtual environment

Steps to create and use a local virtual environment for this project:

- Create the virtual environment and install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip setuptools wheel
pip install -r requirements.txt
```

- Or run the helper script:

```bash
./venv_setup.sh
```

After activation use `deactivate` to exit the virtual environment.
