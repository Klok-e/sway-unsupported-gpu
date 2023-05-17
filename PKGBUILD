pkgname=sway-unsupported-gpu
pkgver=1.0.1
pkgrel=4
pkgdesc="Add session file with --unsupported-gpu option"
arch=('any')
url="https://github.com/LokiVKlokeNaAndoke/sway-unsupported-gpu"
license=('MIT')
depends=('sway' 'vulkan-validation-layers')
source=("$pkgname-$pkgver::git+$url.git#tag=$pkgver")
md5sums=('SKIP')

package() {
  cd "$pkgname-$pkgver"

  install -Dm644 sway-unsupported-gpu.desktop "$pkgdir/usr/share/wayland-sessions/sway-unsupported-gpu.desktop"
}
