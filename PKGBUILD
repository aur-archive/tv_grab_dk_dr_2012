#Maintainer: Louis Tim Larsen <louis(a)louis.dk>

pkgname=tv_grab_dk_dr_2012
pkgver=20140912
pkgrel=1
pkgdesc="XMLTV grabber for dr.dk/tv (Denmark)"
arch=('any')
depends=('xmltv' 'perl-parse-recdescent' 'perl-datetime')
optdepends=(
'mythtv: Homebrew PVR project with separate frontend and backend'
'tvheadend: TV recording server and streaming backend'
'xbmc: Popular standalone HTPC-frontend'
)
license=('GPL3')
url="http://sourceforge.net/projects/xmltvdk/"
source=("$pkgname::http://sourceforge.net/p/xmltvdk/code/HEAD/tree/trunk/$pkgname?format=raw")
md5sums=('2aad1166b143f7f4ae6edc8ee7b922b1')

package() {
	install -Dm755 "$pkgname" "$pkgdir/usr/bin/$pkgname"
}
