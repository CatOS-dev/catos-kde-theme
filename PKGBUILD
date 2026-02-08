pkgname=catos-kde-theme
pkgver=1.0
pkgrel=3
pkgdesc="CatOS KDE Theme"
arch=("any")
url="https://www.catos.info/"
license=("GPL")
source=("$pkgname::git+file://$PWD")
sha256sums=("SKIP")

package() {
cd "$srcdir/$pkgname"
    install -d "$pkgdir/usr"
    if [ -d "usr" ]; then
        cp -r usr/* "$pkgdir/usr/"
    fi
}
