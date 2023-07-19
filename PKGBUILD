pkgname=dmenu-pipewire
pkgver=0.1
pkgrel=1
pkgdesc='Audio sink chooser using Pipewire and Dmenu'
arch=('any')
license=('MIT')
depends=(
  'pipewire'
  'wireplumber'
  'jq'
)
makedepends=()
optdepends=(
  'dmenu'
  'fuzzel'
  'rofi'
)
source=(
  'dmenu-pipewire'
  'dmenu-pipewire.desktop'
)
md5sums=('SKIP' 'SKIP')

package() {
  install -Dm755 "dmenu-pipewire" "$pkgdir/usr/bin/dmenu-pipewire"
  install -Dm644 "dmenu-pipewire.desktop" "$pkgdir/usr/share/applications/dmenu-pipewire.desktop"
}
