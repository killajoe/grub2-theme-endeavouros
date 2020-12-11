# Maintainer: EndeavourOS-Team <info@endeavouros.com>
pkgname=grub2-theme-endeavouros
pkgver=1
pkgrel=1
pkgdesc='new EndeavourOS grub2 theme'
arch=(any)
url='https://github.com/killajoe/'
license=('GPL3')
depends=('grub')
replaces=('grub2-theme-endeavouros')
makedepends=('git')
source=('git+https://github.com/killajoe/grub2-theme-endeavouros')
sha512sums=('SKIP')

package() {
    install -dm 755 $pkgdir/usr/share/grub/themes/EndeavourOS-Default
    cp -r --no-preserve=ownership grub2-theme-endeavouros/EndeavourOS-Default $pkgdir/usr/share/grub/themes/
}
