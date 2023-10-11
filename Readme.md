# Popular GitHub Workflow
> https://github.com/Pythagora-io/gpt-pilot/blob/main/.github/workflows/ci.yml

- Given the name, this workflow appears to be tasked to test the repo's main branch.
- First it creates a docker image, then runs it.
- In the new container, it then appears to setup Python (and only specific versions at that), using `pip` to install some required dependencies.
- The next step appears to be 'linting' the code (which I understand to be an automated audit of the code, which will flag many common issues) using the `flake8` and `ruff` Python packages.
- Finally, appears to run the actual tests using the `pytest` package.

# Hello World GitHub Workflow Repo
> https://github.com/adrienabbey/cs3900-githubexercise