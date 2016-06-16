pkgname=python3-pygame
pkgver=1.9.2pre.20141217
pkgrel=1
pkgdesc="Python game library"
arch=('x86_64')
url="http://www.pygame.org"
license=('LGPL')
depends=( 'python3' 'sdl_mixer' 'sdl_ttf' 'sdl_image' 'portmidi' )
source=(https://bitbucket.org/pygame/pygame/get/fsencoding-ascii.tar.gz)
sha512sums=('')

package() {
        cd pygame-pygame-64f9038c292d
        python config.py -auto
        python setup.py install --root="${pkgdir}" --prefix=/usr
}
