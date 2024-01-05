# cookiecutter-r-project

Template for analysis project in R.

## Usage

1. Create a new environment with `mamba create --name cookiecutter-env cookiecutter pre-commit`.
2. Activate this environment and run `cookiecutter gh:sparklabnyc/cookiecutter-r-project`.

Note, in the background, `git init` and `pre-commit install` have been called.
You can remove the hooks at any time using `rm -rf .git/hooks`.

## Credits

Adapted from [lazappi](https://github.com/lazappi/cookiecutter-r-analysis), [AP](https://github.com/associatedpress/cookiecutter-r-project) and [startyourlab](https://github.com/startyourlab/r-project-template).
