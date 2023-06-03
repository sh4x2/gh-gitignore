# gh-gitignore

`gh` extension to add `.gitignore` file to your project from the templates provided in [github/gitignore](https://github.com/github/gitignore)

## Installation
```
gh extension install sh4x2/gh-gitignore
```

## Usage
```
Usage:
  gh gitignore [COMMAND] [OPTIONS] [TEMPLATE]

Commands:
  add         Adds .gitignore from template in https://github.com/github/gitignore
  list        Lists all template in https://github.com/github/gitignore
  search      Search template in https://github.com/github/gitignore

Options:
  --append    Append template to .gitignore, replaces when not passed
  --help      Displays halp

Examples:
  gh gitignore Python  # Add Python .gitignore
  gh gitignore add Global/VisualStudioCode --append  # Append VSCode to .gitignore
  gh gitignore list  # List templates
  gh gitignore search python  # Search for all 'python' templates
```
