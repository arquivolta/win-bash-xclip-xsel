# Maintainer: Anaïs Betts <support@arquivolta.dev>
# Author: @Konfekt at https://github.com/Konfekt/win-bash-xclip-xsel
pkgname=wsl-xclip-xsel
_clonedname=win-bash-xclip-xsel
pkgver=0.0.1
pkgrel=2
pkgdesc="WSL/Git-Bash binding to xclip and xsel"
arch=('any')
url="https://github.com/Konfekt/win-bash-xclip-xsel"
license=('Unlicense')
makedepends=('git')
conflicts=(	'xclip'
			'xsel')
source=("git+https://github.com/arquivolta/${_clonedname}.git")
sha256sums=('SKIP')


package() {
	install -Dm755 "${srcdir}/${_clonedname}/clip.sh" "${pkgdir}/usr/bin/xclip"
	install -Dm755 "${srcdir}/${_clonedname}/clip.sh" "${pkgdir}/usr/bin/xsel"
}
