# Arkannon's Super Scripts, AKA ASS
ASS is my (Arkannon's) collection of Bash Scripts that I use daily with varying uses.
## What do my scripts do?
### autostart
It is just a basic autostart script. Nothing to write home about. Merely here for the repo
### brb
Silly brb script that plays a tune and sends a message. Dependancies are sox and figlet.
### dance
Another silly script featuring dancing toothless and driftveil city. Dependancies are chafa and sox
### tbs
Yet another silly script that does the Jojo's "To Be Continued" meme. Dependancies are sox and chafa
### toggle & hydro
Whenever toggle activates, it detects whether or not hydro is running, kills it or starts it.
Hydro will send a notification and play the MGS Alert tone every 15-30 minutes
### swwwchange
Runs in background upon startup. Checks to ensure swww-daemon is running and randomly selects a background image to use.
### nixhandle
Handles switching profiles, updating flakes, and keeping your git repo up to date. Works on NixOS and macOS with nix-darwin
## How to I get these scripts?
### Download?
Just download the scripts, silly and edit the paths to work with your system.
### Nix Derivation
I built a derivation **[here](https://github.com/ArkieSoft/nixos/blob/main/modules/ass.nix)**. Confirmed to work with macOS and NixOS. 
Simply add it in and add ``(callPackage ./path/to/ass.nix {})`` to your programs list. The scripts would be added to PATH and can be called like any other application.
## How do I contribute?
Honestly, I would be surprised if anyone would want to contribute, but if you do, feel free to make a PR.
