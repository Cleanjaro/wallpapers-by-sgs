# All wallpapers courtesey of SGS https://github.com/sgse
# Maintainer: David Spink <yorper_protonmail.com>

pkgbase=cleanjaro-wallpapers-by-sgs
pkgname=($pkgbase $pkgbase-hd+)
pkgver=20191116
pkgrel=2
pkgdesc='Cleanjaro Wallpapers by SGS'
arch=('any')
url="https://github.com/Cleanjaro/wallpapers-by-sgs"
license=('GPLv3')
source=("git+$url.git")
sha256sums=('SKIP')

pkgver() {
  date +%Y%m%d
}

package_cleanjaro-wallpapers-by-sgs() {
  conflicts=('cleanjaro-wallpapers-by-sgs-hd+')
    install -d -m755 ${pkgdir}/usr/share/backgrounds/sgs
	cd $srcdir
	cp -R wallpapers-by-sgs/wallpaper/* ${pkgdir}/usr/share/backgrounds/sgs
}

package_cleanjaro-wallpapers-by-sgs-hd+() {
  pkgdesc="Cleanjaro Wallpapers by SGS in 2K & 4K"
  conflicts=('cleanjaro-wallpapers-by-sgs')
    install -d -m755 ${pkgdir}/usr/share/backgrounds/sgs
	cd $srcdir
	cp -R wallpapers-by-sgs/wallpaper-hd+/* ${pkgdir}/usr/share/backgrounds/sgs
}
