# Maintainer: lautaro <tu-email>
pkgname=linux-silvermont-bin
pkgver=PKGVER
pkgrel=1
pkgdesc="Kernel TKG-PDS y Headers optimizados para Silvermont. Compilado usando Clang y Thin"
arch=('x86_64')
url="PKGURL"
license=('GPL')
depends=('coreutils' 'kmod' 'initramfs')
options=('!strip' '!debug')
source=(
  "test.txt::KERNEL_URL"
)

sha256sums=(
  'SKIP'
)

package() {
  install -Dm644 "$srcdir/test.txt" "$pkgdir/usr/share/doc/$pkgname/test.txt"
}

