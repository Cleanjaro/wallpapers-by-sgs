# All wallpapers courtesey of SGS https://github.com/sgse
# Maintainer: David Spink <yorper_protonmail.com>

pkgname='cleanjaro-wallpapers-by-sgs'
pkgver=20191116
pkgrel=1
pkgdesc='Cleanjaro Wallpapers by SGS'
arch=('any')
url="https://github.com/Cleanjaro/wallpapers-by-sgs"
license=('GPLv3')
source=("git+$url.git")
sha256sums=('SKIP')

pkgver() {
  date +%Y%m%d
}

package() {    
    install -d -m755 ${pkgdir}/usr/share/backgrounds/sgs
	cd $srcdir
	cp -R wallpapers-by-sgs/wallpaper/* ${pkgdir}/usr/share/backgrounds/sgs
    install -d -m755 ${pkgdir}/usr/share/icons
	cp -R wallpapers-by-sgs/icon/* ${pkgdir}/usr/share/icons
}

