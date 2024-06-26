# WSL Setup & Commands

**Microsoft Store**

- Windows Subsystem for Linux
- Ubuntu 20.04.6 LTS

**Basic Commands and Updates**

- `sudo apt-get update`
- `sudo apt-get upgrade`
- `clear` (Clears everything)
- CLI (Command Line Interface)

**Homebrew**

- [Homebrew](https://brew.sh/) is a package manager. It allows us to utilize different packages.
- `brew upgrade` (Scans every dependency and upgrades)

**Installation**

- Install cli, azure, git and config, terraform
- Install zsh

**Information about Terminal & Shell**

- Shell is the unit that executes the commands entered.
- Terminal contains the shell.
- Ubuntu's terminal isn't visually appealing, consider an alternative.
- By default, it will use bin/bash. Switch to using bin/zsh for faster performance.
- Powerlevel10k for Zsh offers better performance.

**File Operations**

- `pwd` (To see current directory)
- `touch index.html` (Create file)
- `nano` (To write code)
- `mkdir A` (Creates directories)
- `touch B.txt` (Creates text files)
- `rm -rf A` (Removes directories or files)

**VS Code**

- `code Copilot` (Open Copilot’s folder)
- View → Terminal (Open the terminal)
- `ls -a` (Shows all files including hidden ones)

**Python/Python Server**

- `python3 -m uvicorn copilot-api-server:app --reload --host 0.0.0.0 --port 8088`
- `python3 -m streamlit run copilot-api-web-client.py`
- `python3 copilot-cli.py --chat`
- `export FAISS_ENABLE_GPU=ON`
- `python -m venv myenv` (To create a virtual environment)
- `.\\myenv\\Scripts\\activate`

**Other Commands**

- Reload VSCode → Ctrl + shift + P
- Run `curl <http://helsinki.fi`> (To get the output)
- `mkdir /usr/src/app` (Creates directory)

