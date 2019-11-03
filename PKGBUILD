# All wallpapers courtesey of SGS https://github.com/sgse
# Maintainer: David Spink <yorper_protonmail.com>

pkgname='cleanjaro-wallpapers-by-sgs'
pkgver=20191103
pkgrel=1
pkgdesc='Cleanjaro Wallpapers by SGS'
arch=('any')
url="https://github.com/Cleanjaro/wallpapers-by-sgs"
license=('GPLv3')
source=("https://github.com/Cleanjaro/wallpapers-by-sgs/tree/master/wallpaper/cleanjaro-bubbles-2160p-sgs.png"
	"https://github.com/Cleanjaro/wallpapers-by-sgs/tree/master/wallpaper/cleanjaro-kdemeoz-2160p-sgs.png"
	"https://github.com/Cleanjaro/wallpapers-by-sgs/tree/master/wallpaper/cleanjaro-sinister-2160p-sgs.png"
	"https://github.com/Cleanjaro/wallpapers-by-sgs/tree/master/wallpaper/cleanjaro-t-01-2160p-sgs.png"
	"https://github.com/Cleanjaro/wallpapers-by-sgs/tree/master/wallpaper/cleanjaro-wwt-01-2160p-sgs.png")
sha256sums=('e5f57b83bd3c2dddf8ba16638c78c38423525c022860876cbb29e3b341f91e89'
            'ec2d9caed506baa6f00fe477442c10e67c40a642cc8f0b74e2e38e4762acc30a'
            'be714fe912e6a3e5969b59dddca62741317d0c2ac0a7d826db34deaf411a0d1d'
            'adffefbe87b05a866926213a5a79d539b7e1d79ec8bfd1e50009f17f333ef2eb'
            '1522123d94016a18f60745b0ee29e41739a18694cfe8613cf53068d1f746b7c5')

pkgver() {
  date +%Y%m%d
}

package() {    
    install -d -m755 ${pkgdir}/usr/share/backgrounds
	cd $srcdir
	cp -R * ${pkgdir}/usr/share/backgrounds
}

