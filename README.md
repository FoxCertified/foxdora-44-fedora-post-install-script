
# Foxdora 44 Post-Install Script for Fedora 44
![Foxdora 44 Banner](https://github.com/FoxCertified/foxdora-fedora-post-install-script/blob/main/Foxdora44.png)

## How to run the script:

 1. [Download latest release](https://github.com/FoxCertified/foxdora-fedora-post-install-script/releases/download/release/Foxdora_44_Post-Install_Script.tar.gz)
 2. Move *emphasized text*
 3. List
 4. List

Start the script by typing `./start-foxdora.sh` into the terminal and pressing enter.

You can also download the latest files yourself:

[Download Latest Repo](https://gitlab.com/fox-does-stuff/foxdora-44-post-install-script/-/archive/main/foxdora-44-post-install-script-main.tar.gz?ref_type=heads)

  

# What does it do?

### Short Version

##### The following will be done:

- Install the latest updates

- Enables RPM Fusion repositories in DNF

- Enables Flathub in Flatpak

- Enables full Multimedia support

- Applies quality of life tweaks to DNF and increases graphics card cache for smoother gameplay

- Applies emoji fallback font for Unicode 17

- Installs helpful system utilities such as BTRFS Assistant

- Defaults shell to zsh for colored syntax highlighting in the terminal

##### You can opt into:

- Installing the Nvidia Graphics Drivers, GTX 800/900/10/16 and RTX20/30/40/50 Supported

- Installing extra utility applications

- Installing Vivaldi web browser

- Installing MullvadVPN

- Installing gaming applications

- Installing artist applications, by category
### Long Version:
###### The following will be done:
The RPM Fusion repository is enabled alongside Flathub for Flatpak.
the Fedora Flatpak source is disabled, as Flathub has everything it has and more.
The latest software updates are then installed.

Third-party codecs that Fedora can not include by default are installed from RPM Fusion, MESA is also switched to the FreeWorld version.

## Example

Depending on what you are making, it can be a good idea to include screenshots or even a video (you'll frequently see GIFs rather than actual videos). Tools like ttygif can help, but check out Asciinema for a more sophisticated method.
  

## Project status

I will keep working on this as long as I keep using Fedora :)
