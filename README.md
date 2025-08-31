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

## Setup

Run this setup by (update inventory as needed):

```bash
ansible-playbook -i inventory.yml setup-ubuntu.yml --ask-become-pass --ask-pass


``````
## Additional apps not installed by the script

Still needs manual installing:
- IntelliJ IDEA
- Kitty terminal
