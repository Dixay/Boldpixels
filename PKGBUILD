pkgname=ttf-boldpixels
pkgver=1.5
pkgrel=1
pkgdesc="BoldPixels TrueType font"
arch=('any')
url="https://github.com/TymonMarek/ttf-boldpixels"
license=('custom:CC-BY-SA-4.0')
depends=()
source=("BoldPixels.ttf" "LICENSE")
sha256sums=('bdee4cb0d6087bdebeb8a7cd1aeb3a44441ba9d1734cd1502f76acc25000d32e'
            '36cade70e42d0cbe06ba011a9e3e47a1e3f22af80af0a9bd70528e7ea1e63bd8')

package() {
    install -Dm644 "BoldPixels.ttf" "$pkgdir/usr/share/fonts/TTF/BoldPixels.ttf"
    install -Dm644 "LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
