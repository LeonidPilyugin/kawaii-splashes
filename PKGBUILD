# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-splashes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii KDE Plasma splashes.'
groups=(kawaii)
url='https://github.com/LeonidPilyugin/kawaii-splashes'
arch=(x86_64)
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('84eb0e66d17dd2f766db1739ebd509c1bd9203a9e62a0862849581cea40c34d5')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
    cp -r $srcdir/* $dir/
}

