# Maintainer: A. Husen <hello@husen.id>
pkgname=nonicons-font
pkgver=r42.8633191
pkgrel=1
pkgdesc="A set of SVG icons representing programming languages, designing & development tools."
arch=('any')
url="https://github.com/yamatsum/nonicons"
license=('unknown')
source=("${url}/raw/master/dist/nonicons.ttf")
sha512sums=("ef3203ed4f5a1fc25e9216684293456e1ee48d51b7098521049369bed85604672a6f6cf12f94367efbf5afedddcb2dfc70e44268e36de37cbef5f12b11cacdb8")

package() {
    install -dm755 "$pkgdir/usr/share/fonts/TTF"
    install -Dm644 "${srcdir}/"*.ttf "${pkgdir}/usr/share/fonts/TTF"
}

