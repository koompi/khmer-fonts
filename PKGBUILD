pkgname=khmer-fonts
pkgver=20210216
pkgrel=1
pkgdesc="Most used Khmer fonts"
arch=('any')
url="https://github.com/koompi/khmer-fonts"
source=("git+https://github.com/koompi/khmer-fonts.git")
md5sums=('SKIP')

package() {

    install -dm755 "${pkgdir}"/usr/share/fonts/l
    install -dm755 "${pkgdir}"/usr/share/fonts/n
    install -dm755 "${pkgdir}"/usr/share/fonts/t
    install -dm755 "${pkgdir}"/usr/share/fonts/TTF
    cd "${srcdir}/${pkgname}/"fonts/l
    install -m644 *.ttf "${pkgdir}/"usr/share/fonts/l/
    cd "${srcdir}/${pkgname}/"fonts/n
    install -m644 *.ttf "${pkgdir}/"usr/share/fonts/n/
    cd "${srcdir}/${pkgname}/"fonts/t
    install -m644 *.ttf "${pkgdir}/"usr/share/fonts/t/
    cd "${srcdir}/${pkgname}/"fonts/TTF
    install -m644 *.ttf "${pkgdir}/"usr/share/fonts/TTF/
}
