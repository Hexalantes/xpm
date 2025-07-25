pkgname=xpm
pkgver=1.0.0
pkgrel=1
pkgdesc="XPM - A simple shell-based Pacman and AUR helper for Arch Linux and derivatives."
arch=('any')
url="https://github.com/hexalantes/xpm"
depends=('bash' 'curl' 'wget' 'tar' 'git' 'zstd' 'libarchive' 'coreutils' 'jq' 'pacman' 'sudo' 'xz' 'base-devel')
source=("xpm")
md5sums=('SKIP')
license=('GPL')

package() {
  install -Dm755 "$srcdir/xpm" "$pkgdir/usr/bin/xpm"
}

