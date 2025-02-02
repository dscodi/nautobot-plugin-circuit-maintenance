# Contributing to the App

The project is packaged with a light [development environment](dev_environment.md) based on `docker-compose` to help with the local development of the project and to run tests.

The project is following Network to Code software development guidelines and is leveraging the following:

- Python linting and formatting: `black`, `pylint`, `bandit`, `flake8`, and `pydocstyle`.
- YAML linting is done with `yamllint`.
- Django unit test to ensure the plugin is working properly.

Documentation is built using [mkdocs](https://www.mkdocs.org/). The [Docker based development environment](dev_environment.md#docker-development-environment) automatically starts a container hosting a live version of the documentation website on [http://localhost:8001](http://localhost:8001) that auto-refreshes when you make any changes to your local files.

To contribute, follow this workflow.

1. Open an issue
2. Get approval from one of the codeowners before working on the issue
3. If working on the issue, assign the issue to yourself
4. Fork the Project and Create a branch in the fork
5. Open a PR into develop, from the branch in your fork
6. Get peer review and approval to merge from one of the codeowners
7. Once approval has been gained, the PR will be merged into develop
8. One of the codeowners will enumerate the features added per the contributor's PR when a tagged release is merged into main

## Release Policy

Releases are on a somewhat adhoc basis as needed. A more formal release process may be decided upon in the future.
