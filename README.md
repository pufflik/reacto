Reacto is a set of CLI commands to maintain react.js apps and components. It is mostly a wrapper around https://github.com/audreyr/cookiecutter with some additional features like adding additional parts (like actions or routes) into existing component.

The main reason why it is not an npm, but pypi package is that there is no cookiecutter port for node.js with non-CLI API.

## Installation
Simply install pypi package:
```shell
pip install reacto
```

CLI script will deploy into some of your `bin/` directories, make sure it is listed in `$PATH`.

## Component structure
*To be edited*

## Available commands and options

### `start_app`
*Not yet avialable*

### `start_component [options] <component path>`
Start new component. You can pass absolute/relative path or just compoentn name, in which case component will be created in current directory.

#### `--actions`
If passed `actions.js` file created.

#### `--no-flow`
*To be edited*

#### `--reducers`
If passed `reducers.js` file created.

#### `--routes`
If passed `routes.js` file created.
