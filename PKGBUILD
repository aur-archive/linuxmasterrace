# Maintainer: Czipperz <czipperz@gmail.com>
pkgname=linuxmasterrace
pkgver=1.2
pkgrel=6
pkgdesc="Adds the 'Arch is the best' wiki page into your /usr/share/arch/ folder"
url="https://wiki.archlinux.org/index.php/Arch_is_the_best"
arch=('any')
makedepends=()
depends=('rakudo')
conflicts=()
backup=()
install=install.install
source=('https://raw.githubusercontent.com/czipperz/archIsTheBest/master/archIsTheBest.html' 'https://raw.githubusercontent.com/czipperz/archIsTheBest/master/archIsTheBest.md' 'https://raw.githubusercontent.com/czipperz/archIsTheBest/master/archIsTheBest')

package() {
	install -Dm755 archIsTheBest.html "$pkgdir"/usr/share/arch/archIsTheBest.html
	install -Dm755 archIsTheBest.md "$pkgdir"/usr/share/arch/archIsTheBest.md
	install -Dm755 archIsTheBest "$pkgdir"/usr/bin/lmr
}
md5sums=('0ab8b403ea8c17395e0700b1146fdc90'
         'da70b2e53004d76a1041e1e9177419dc'
         'SKIP')
