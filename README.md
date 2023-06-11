## Installation

Install Debian from unofficial images that include firmware:

<https://cdimage.debian.org/cdimage/unofficial/non-free/cd-including-firmware/>

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
  Numix-Circle for icons, DMZ-White for curors

- Set interface font in Gnome Tweaks: Ubuntu

- Download and set wallpaper:
  <https://www.deviantart.com/mushcube/art/Annapurna-474805362>

- Install uBlock Origin in Google Chrome
