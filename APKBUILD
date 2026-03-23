# Reference: <https://postmarketos.org/devicepkg>
maintainer=""
pkgname=device-gm-mehmet
pkgdesc="General Mobile E-Tab 4"
pkgver=1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="armv7"
options="!check !archcheck"
depends="
	linux-postmarketos-exynos4
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="
	deviceinfo
	modules-initfs
"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
e5e2773de55ec0e24cc07403f14bf90b75dde3b9f85cd89df595f0bbb3484afc668ec91ac534caa7b5ef64e6a1a0e3526710770d2f5a4ca302887a95e3e134db  deviceinfo
e70bae17df23dcaaaea0e2d3616556f04baa23f8ee1357785c0f539bf97282d8ddff53953e155b72689bb73beb38c2da3d08de2a61e866684edfa10a6593885d  modules-initfs
"
