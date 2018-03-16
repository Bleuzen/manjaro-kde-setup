# Maintainer: Bleuzen <supgesu at gmail dot com>

pkgname=bleuzen-manjaro-kde-setup
pkgver=2018.03.16
pkgrel=1
pkgdesc="My Manjaro KDE setup"
arch=("x86_64")
url="https://github.com/Bleuzen/manjaro-kde-setup"
depends=("pamac"
         "pamac-tray-appindicator"
         "xdg-desktop-portal-gtk"
         "xdg-desktop-portal-kde"
         "flatpak"
         "rsync"
         "bash-completion"
         "wget"
         "zip"
         "frei0r-plugins"
         "xorg-xrandr"
         "yaourt")
optdepends=("powerpill"
            "pacserve"
            "chromium"
            "latte-dock"
            "gimp"
            "audacity"
            "obs-studio"
            "redshift" "plasma5-applets-redshift-control"
            "file-roller"
            "gparted" "gnome-disk-utility"
            "tk"
            "gnome-calculator"
            "soundkonverter"
            "kid3"
            "lame"
            "vorbis-tools"
            "opus-tools"
            "flac"
            "zsh" "zsh-autosuggestions" "zsh-completions" "manjaro-zsh-config"
            "keepassxc"
            "adapta-gtk-theme" "adapta-kde" "kvantum-theme-adapta" "papirus-icon-theme"
            "plasma-vault" "cryfs"
            "libva-vdpau-driver"
            "android-file-transfer"
            "wine" "wine-mono" "wine_gecko" "winetricks"
            "pulseeffects"
            "youtube-dl"
            "telegram-desktop"
            "testdisk"
            "wireshark-qt"
            "lollypop")
conflicts=("octopi-notifier-frameworks")
install=$pkgname.install

package() {
  mkdir -p "$pkgdir/usr/bin/"
  
  for file in "scripts/*"
  do
    install -m755 $file "$pkgdir/usr/bin/"
  done

  # Permission example:
  #install -Dm644
}
