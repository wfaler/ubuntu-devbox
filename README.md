# Devbox for Ubuntu 24.04, Arm64 or Amd64 architectures.

Installs and sets up the following:
* Docker
* Fish shell with a nice theme
* SDK Man 
* JDK 21 Temurin
* Gradle
* Latest Python with Poetry for package management
* Latest LTS Node and Claude Code 
* Latest Golang
* Neovim with a nice config and theme for the above languages and a few more (Rust, Scala, Typescript)

## Why?
Agentic AI opens a lot of possibilities, but also risks, such as prompt injection and just bad "oopsies". Probably a good idea to keep it separate from your main system.
I use this inside a Ubuntu Parallels VM on my Mac, but should work on any Ubuntu 24.04 system.

## Setup

Run this setup by (update inventory as needed):

```bash
ansible-playbook -i inventory.yml setup-ubuntu.yml --ask-become-pass --ask-pass


``````
## Additional apps not installed by the script

Still needs manual installing:
- IntelliJ IDEA
- Kitty terminal
