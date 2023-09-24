# Conventions
This file details what conventions I plan to follow.

## Git Commit
Git commit messages will follow 'Convention Commits': https://www.conventionalcommits.org/en/v1.0.0/
### Structure
```
<type>[optional scope]: <description> 
[optional body] 
[optional footer(s)]
```

### Type
Must be one of the following:

* **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
* **ci**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **perf**: A code change that improves performance
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* **test**: Adding missing tests or correcting existing tests

## README
1. Project banner
2. Shields
3. Single sentence description
4. Image/GIF (showing usage, gameplay, etc)
5. Installation guide
6. Configuration options
7. Usage information
8. How to contribute
9. Other

## Python
Python code will be written according to PEP8: https://peps.python.org/pep-0008/