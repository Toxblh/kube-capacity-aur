# Maintainer: Anton Palgunov <toxblh@gmail.com>

pkgname=kube-capacity
_pkgname=kube-capacity
pkgver=${TAG}
pkgrel=${TAG_RELEASE}
pkgdesc="A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster"
arch=('x86_64')
url="https://github.com/robscott/kube-capacity"
source=("https://github.com/robscott/kube-capacity/releases/download/$pkgver/kube-capacity_"$pkgver"_Linux_x86_64.tar.gz")
sha256sums=('${SHA256SUM}')
options=(!strip)
arch=('x86_64')
license=('Apache-2.0')

package() {
  install -Dm 755 "$srcdir/kube-capacity" "$pkgdir/usr/bin/kube-capacity"
}
