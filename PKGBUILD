# Maintainer: Aurélien Ooms <aurelien.ooms@gmail.com>
pkgname=memoize-rust
pkgver=2.0.0
pkgrel=1
epoch=
pkgdesc="Cache executable calls"
arch=(any)
url="https://github.com/aureooms/memoize"
license=('AGPL-3.0')
groups=()
depends=('bash' 'coreutils')
makedepends=('git' 'rust')
checkdepends=()
optdepends=()
provides=('memoize')
conflicts=('memoize')
replaces=()
backup=()
options=()
install=
source=("https://github.com/aureooms/memoize/archive/v${pkgver}.tar.gz")
noextract=()
md5sums=('SKIP')

package() {
	cd "$srcdir/memoize-$pkgver"
	make DESTDIR="$pkgdir" install-rust
}
