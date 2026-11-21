# Forge downloads

Install guide: https://devstudiosdigital.github.io/forge-releases/

Download `forge-install-<version>.sh` from the [Releases](https://github.com/DevStudiosDigital/forge-releases/releases) page, copy it to the server, and run `sudo sh forge-install-<version>.sh`. It needs no internet access.

## Example install

A full install of Forge 0.1.8 on a blank Ubuntu 24.04 server with no internet access and no Docker or Podman: the installer checks the server, installs Docker from the file, asks for an admin and the model (Ollama with Gemma 3 1B, given as an image file and a model folder), starts Forge and checks that the model answers.

https://github.com/DevStudiosDigital/forge-releases/raw/main/forge-install-0.1.8.mp4
