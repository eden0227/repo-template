# Repository Template

> A skeleton template for project repositories.

---

## Table of Contents

-   [About](#about)
-   [Tech Stack](#tech-stack)
-   [Starter Kit](#starter-kit)
-   [Changelog](#changelog)
-   [Contributing](#contributing)
-   [Acknowledgements](#acknowledgements)
-   [Licence](#licence)

---

## About

<TODO>

```
hello, world
```

> [!IMPORTANT]
> Refer to official documentation for recommended best practices.

---

## Tech Stack

-   Version Control: **Git**
-   Remote Repository Hosting: **GitHub**
-   Integrated Development Environment: **Visual Studio Code**

---

## Starter Kit

### vs code

```
- extensions
- command palette
- git gui
- wsl remote connection
```

### powershell (default)

```
- linux equivalent commands
- function prompt { "$( (Get-Location | Split-Path -Leaf) )> " }
- function prompt { "PS $($executionContext.SessionState.Path.CurrentLocation)$('>' * ($nestedPromptLevel + 1)) " }
- winget source update
- winget upgrade --id <Id> -e
- wsl --help
- wsl --update
- gcc, python, node, git
- python -m pip install --upgrade pip
- pip list
- pip install <package_name>
```

### ubuntu-22.04 (wsl)

```
- linux commands
- PS1='\W \$ '
- source ~/.bashrc
- exit
- sudo apt update && sudo apt upgrade
- sudo apt install <package_name>
- apt list --installed
- gcc, python3, node, git, make, libcs50, valgrind
- python3 -m pip install --upgrade pip
- pip list
- pip install <package_name>
```

### msys2 (mingw64)

```
- pacman -Suy
- gcc, make, git
```

### git version control

```
- ssh keys
- credential helper
- git commands
- repository template
```

---

## Changelog

### [v2.0] - 2025-12-7

-   Add Python and C boilerplates ([src](src))
-   Add Makefile text file
-   Add starter kit section ([README.md](README.md))

### [v1.1] - 2025-9-16

-   Add placeholder files (.gitkeep)

### [v1.0] - 2025-9-16

-   Add basic project repository template

### [v0.1] - 2025-9-16

-   Initialise Git repository
-   Add MIT licence ([LICENSE](LICENSE))

---

## Contributing

_Contribution and guidelines are not yet available (to be implemented in the future)_

---

## Acknowledgements

### Credits

-   Eternal gratitude to God, the Most Gracious, the Most Merciful.

### References

-   https://www.youtube.com/watch?v=xvFZjo5PgG0&ab_channel=Duran

---

## Licence

This project is licensed under the [MIT Licence](LICENSE).
