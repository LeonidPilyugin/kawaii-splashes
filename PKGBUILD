# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-splashes
pkgver=2.0
pkgrel=1
pkgdesc='Kawaii KDE Plasma splashes.'
groups=(kawaii)
url='https://github.com/LeonidPilyugin/kawaii-splashes'
arch=(x86_64)
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('10d8fbb658fb07ab7bd76bda5383989c91fb52f06458cfd416b9ee6a305c0f2b')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
    cp -r $srcdir/* $dir/
}

