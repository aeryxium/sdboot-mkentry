# Maintainer: Aeryxium <aeryxium+arch@gmail.com>
pkgname='sdboot-mkentry'
pkgver=1
pkgrel=1
pkgdesc='Create a systemd-boot entry file with given parameters'
arch=('x86_64')
url='https://github.com/aeryxium/sdboot-mkentry'
license=('GPL')
source=(
	'sdboot-mkentry'
)
sha256sums=('7ef022d472cde13c1d0740b1aab895623f5ea70da8d0c9e5740d34420795803d')
depends=(
	'sed' 'awk'
)
package() {
	install -Dm 0644 "sdboot-mkentry"    "$pkgdir/usr/bin/sdboot-mkentry"
}
