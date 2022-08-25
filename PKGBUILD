# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-splashes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii splashes.'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('97a809ddc2abbdf28c0e7a3133eecdeddc3b93eec1012086375ed7118307681f')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
	cp -r $srcdir/* $dir/
}

