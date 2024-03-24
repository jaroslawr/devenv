## Installation

Install Debian from DVD image:

<https://cdimage.debian.org/cdimage/weekly-builds/amd64/iso-dvd/>

After installing Debian, install git and ansible, checkout the repo and run the
playbook:

    su -l
    apt-get install git ansible
    git clone https://github.com/jaroslawr/devenv.git
    cd devenv
    ansible-playbook devenv.yml

## Manual setup steps

- Enable "User themes" extension in "Extensions" Gnome app

- Set themes in Gnome Tweaks: Yaru-red for shell and legacy applications,
  Papirus for icons, DMZ-White for curors

- Set fonts in Gnome Tweaks: Ubuntu Regular 11 Interface and Legacy Window
  Titles, Carlito 12 for Documents, Monospace 11 for Monospace

- Download and set wallpaper:
  <https://wallhaven.cc/w/858x21>

- Install uBlock Origin in Google Chrome
