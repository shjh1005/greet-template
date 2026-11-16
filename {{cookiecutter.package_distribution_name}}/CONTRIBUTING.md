# Contributing to {{ cookiecutter.package_distribution_name }}

## Set up for development

```bash
python -m pip install -e .
```

## Run the tests

```bash
python -c "from {{ cookiecutter.package_import_name }} import greet; print(greet('Hee'))"
```

기대 출력은 `Hello, Hee!`이다.

## Send a change

1. `main`에서 브랜치를 만들고 변경을 커밋한다.
2. 브랜치를 push한다.
3. `main`으로 PR을 연다.
