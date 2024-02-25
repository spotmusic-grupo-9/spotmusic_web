# SpotMusic API

## Documentação

Este projeto faz parte do SpotMusic e tem um repositorio dedicado para documentações: [spotmusic_docs](https://github.com/spotmusic-grupo-9/spotmusic_docs)

## Pastas

```
.
├── app                  # "app" is a Python package
│   ├── __init__.py      # this file makes "app" a "Python package"
│   ├── main.py          # "main" module, e.g. import app.main
│   ├── dependencies.py  # "dependencies" module, e.g. import app.dependencies
│   └── routers          # "routers" is a "Python subpackage"
│   │   ├── __init__.py  # makes "routers" a "Python subpackage"
│   │   └── users.py     # "users" submodule, e.g. import app.routers.users
├── requirements
│   │   └── base.txt     # "base" basic installation requirements
│   │   └── dev.txt      # "dev" development installation requirements
│   │   └── prod.txt     # "prod" production installation requirements
├── tests
│   │   ├── __init__.py  # makes "tests" a "Python subpackage"
│   │   └── users.py     # "users" tests of app.routers.users
└── .env
```

_referencia: [fastapi](https://fastapi.tiangolo.com/tutorial/bigger-applications/)_
