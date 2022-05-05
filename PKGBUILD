# Contributor: Bhushan Shah < bshah at kde dot org >
pkgname=android-headers-30
pkgver=11.0.0
pkgrel=1
pkgdesc="Android Platform Headers from AOSP releases"
arch=('any')
url="https://github.com/droidian/android-headers-30"
license=('Apache')
makedepends=('git' 'libffi')
provides=('android-headers')
conflicts=('android-headers-28' 'android-headers-29')
source=('android-headers::git+https://github.com/droidian/android-headers-30')
md5sums=('SKIP')

package() {
    cd android-headers
    make PREFIX="/usr" DESTDIR="$pkgdir/" install
}
