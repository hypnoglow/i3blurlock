# Maintainer: Igor Zibarev <hypnoglow@gmail.com>

pkgname=i3blurlock
pkgver=20160413
pkgrel=1
pkgdesc="Simple blur lock screen for i3. Works on top of i3lock."
arch=('any')
license=('custom:MIT')
depends=(
    'i3-wm'
	'i3lock'
    'scrot'
    'imagemagick'
    'xkb-switch-git'
)
optdepends=(
    'lightdm-gtk-greeter: switch user with lightdm'
)
source=(
    'i3blurlock'
    'LICENSE'
)
md5sums=(
    'SKIP'
    'SKIP'
)

package() {
	install -Dm755 $srcdir/$pkgname $pkgdir/usr/bin/i3blurlock
    install -Dm644 $srcdir/LICENSE $pkgdir/usr/share/licenses/$pkgname/LICENSE
}
