# gh-gitignore

`gh` extension to add `.gitignore` file to your project from the templates provided in [github/gitignore](https://github.com/github/gitignore)

## Installation
```
gh extension install sh4x2/gh-gitignore
```

## Usage
```
gh gitignore [OPTIONS] [TEMPLATE]
Adds .gitignore from templates in https://github.com/github/gitignore

Options:
  --append  Append template to .gitignore, replaces when not passed
  --help    Displays halp

Examples:s
  gh gitignore Python  # Add Python .gitignore
  gh gitignore --append Global/VisualStudioCode  # Append VSCode to .gitignore
```
