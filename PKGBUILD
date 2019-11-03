# All wallpapers courtesey of SGS https://github.com/sgse
# Maintainer: David Spink <yorper_protonmail.com>

pkgname='cleanjaro-wallpapers-by-sgs'
pkgver=20191103
pkgrel=0.1
pkgdesc='Cleanjaro Wallpapers by SGS'
arch=('any')
url="https://github.com/Cleanjaro/wallpapers-by-sgs"
license=('GPLv3')
makedepends=('git')
source=("placeholder")
sha256sums=('placeholder')

pkgver() {
  date +%Y%m%d
}

package() {    
    install -d -m755 ${pkgdir}/usr/share/backgrounds
	cd $srcdir
	cp -R * ${pkgdir}/usr/share/backgrounds
}

