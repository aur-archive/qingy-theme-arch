# $Id: PKGBUILD 78820 2012-10-25 06:47:28Z foutrelis $
# Maintainer: Eric Bélanger <eric@archlinux.org>
# Contributor (arch theme): Thayer Williams

pkgname=qingy-theme-arch
pkgver=2.0
pkgrel=3
pkgdesc="Arch Linux themes for qingy"
arch=('any')
url="http://qingy.sourceforge.net/"
license=('custom')
depends=('qingy')
source=("ftp://ftp.archlinux.org/other/community/${pkgname}/${pkgname}-${pkgver}.tar.bz2")
sha1sums=('4271745da9f28490f69afd6158f4d2702aeb2397')

package() {
  cd "${srcdir}/${pkgname}-${pkgver}"
  install -d "${pkgdir}/usr/share/qingy/themes"
  cp -r * "${pkgdir}/usr/share/qingy/themes/"
  install -D -m644 arch/Vera.copyright "${pkgdir}/usr/share/licenses/${pkgname}/Vera.copyright"
  install -D -m644 arch/dmz.copyright "${pkgdir}/usr/share/licenses/${pkgname}/dmz.copyright"
  install -D -m644 arch/icons.copyright "${pkgdir}/usr/share/licenses/${pkgname}/icons.copyright"
}
