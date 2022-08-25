# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-splashes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii splashes.'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('09c3fa3c499b610db0e7a079ebbd177e56f11f84bfdd0ddcf045e4e09135a682')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
	cp -r $srcdir/* $dir/
}

