# Maintainer: Perkelo <alessandro [dot] scala [eight] [at] gmail [dot] com>

pkgname=ttf-a-goblin-appears
pkgver=1.0
pkgrel=1
pkgdesc="A Goblin Appears Font"
arch=(any)
license=('FSLA')
depends=(fontconfig xorg-font-utils)
url="https://www.fontspace.com/a-goblin-appears-font-f30019"
source=("a-goblin-appears-font.zip::https://get.fontspace.co/download/family/l2r2m/819c16ad096f48f9abe5a0525e06335a/a-goblin-appears-font.zip")
sha256sums=('519c2f5cf4cdb67369e7cb7d6726cf2bee60eb6eb2ac3c595da948e01c98fc64')
install=$pkgname.install

package() {
    install -d "$pkgdir/usr/share/fonts/TTF"
    install -m644 "$srcdir/AGoblinAppears-o2aV.ttf" "$pkgdir/usr/share/fonts/TTF/"
    install -d "$pkgdir/usr/share/licenses/ttf-a-goblin-appears"
    install -m644 "$srcdir/misc/FSLA_NonCommercial_License-4726.html" "$pkgdir/usr/share/licenses/ttf-a-goblin-appears/LICENSE"
}
