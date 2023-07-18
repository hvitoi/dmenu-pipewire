pkgname=dmenu-audio-sink
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
  'dmenu-audio-sink'
  'dmenu-audio-sink.desktop'
)
md5sums=('SKIP' 'SKIP')

package() {
  install -Dm755 "dmenu-audio-sink" "$pkgdir/usr/bin/dmenu-audio-sink"
  install -Dm644 "dmenu-audio-sink.desktop" "$pkgdir/usr/share/applications/dmenu-audio-sink.desktop"
}
