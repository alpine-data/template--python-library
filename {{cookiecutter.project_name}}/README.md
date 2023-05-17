# {{ cookiecutter.project_name }}

{{ cookiecutter.description }}

## Usage

## Development

```bash
$ git clone $REPOSITORY_URL
$ cd {{ cookiecutter.project_name }}
$ conda create -p ./env python=3.10
$ conda activate ./env

$ poetry install
```

### Code Style and Quality

The project uses a set of code formatting and code quality tools. To properly format the code, run:

```bash
$ poe style
```

To check overall quality of the code, run:

```bash
$ poe quality
```

Run these commands before pushing code to the central repository. Code Quality checks will also be executed during automated build. The build will fail, if issues are detected.

### Testing

The project includes a set of unit tests. When adding new features or changing features, these unit tests should be extended/ adapted. To run all tests, execute:

```bash
$ poe test
```


## License

{{ cookiecutter.license }}