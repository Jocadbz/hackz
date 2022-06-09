# Maintainer: Jocadbz <jocadbz at gmail dot com>

pkgname=hackz
pkgver=1.0.0
pkgrel=2
pkgdesc="A script to hack NASA as a cool kid"
arch=('any')
url="https://github.com/Jocadbz/hackz"
license=('MIT')
depends=('python')
provides=('hackz')
source=("https://github.com/Jocadbz/hackz/releases/download/1.0.0/hackz" "https://raw.githubusercontent.com/Jocadbz/hackz/main/LICENSE")
noextract=(hackz)
md5sums=('4c225c9c0448a21e03aa6cfd65ebc766'
         '24d2515d25da0a3df290a1e8ccb01d49')

package() {
        install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
        install -dm755 $pkgdir/usr/bin
	cp $pkgname $pkgdir/usr/bin
	chmod +x $pkgdir/usr/bin/$pkgname
}
