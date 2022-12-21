[`cookiecutter`](./cookiecutter) is a Jinja-templated project.

We can generate a new project with:
```shell
docker run --rm --platform linux/amd64 -w /app -v "$(pwd)":/app -e LC_ALL=C.UTF-8 -t cookiecutter/cookiecutter /app/cookiecutter
```
