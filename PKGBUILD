# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Elijah Lynn <elijah@elijahlynn.net>
pkgname=aws-session-manager-plugin
pkgver=1
pkgrel=1
epoch=
pkgdesc=""
arch=('x86_64')
url="https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html"
license=('GPL')
groups=()
depends=()
makedepends=('rpmextract')
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=("https://s3.amazonaws.com/session-manager-downloads/plugin/latest/linux_64bit/session-manager-plugin.rpm")
noextract=()
md5sums=('6baddc350f16e0b01dbffdb99a06f08b')
validpgpkeys=()


package() {
       cp -r etc $pkgdir/ 
       mkdir --parents $pkgdir/usr/local/bin
       cp usr/local/sessionmanagerplugin/bin/session-manager-plugin $pkgdir/usr/local/bin/
}

