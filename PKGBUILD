# Maintainer: Elie Bouttier <elie@bouttier.eu.org>
# Contributor: Pierre Carrier <pierre@gcarrier.fr>
_ghuser=freelan-developers
pkgname=freelan-buildtools
pkgver=1.2
_pkgid=df783b5
pkgrel=1
pkgdesc="A set of build tools for FreeLAN related projects"
arch=(any)
url="http://www.freelan.org/"
license=('GPL')
makedepends=('scons' 'python2-setuptools')
source=("https://github.com/$_ghuser/$pkgname/tarball/$pkgver")
md5sums=('0ba1bccba608a04d04b1d05307a345aa')

package() {
  cd "$srcdir/$_ghuser-$pkgname-$_pkgid"
  python2 setup.py install --root="$pkgdir/" --optimize=1
}
