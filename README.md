# dagster-tute

- https://github.com/dagster-io/dagster

```
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

```
dagster dev --help
dagster dev -f example.py
```

```
dagster-webserver --help
dagster-webserver -f example.py
```

- http://127.0.0.1:3000

## Tutorial

- https://docs.dagster.io/tutorial

```
dagster project from-example --example tutorial
cd tutorial
pip install -e ".[dev]"
dagster dev
```
