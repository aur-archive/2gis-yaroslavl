# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>
     
pkgname=2gis-yaroslavl
pkgver=31
pkgrel=1
pkgdesc="Map of Yaroslavl for 2GIS, January 2013"
arch=('i686' 'x86_64')
url="http://yaroslavl.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Yaroslavl-31.orig.zip")
md5sums=('4c1fe3449de1c416273ba48fc93766c7')
     
build() {
     
   cd $startdir
     
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Yaroslavl.dgdat "${startdir}/pkg/opt/2gis/yaroslavl.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Yaroslavl.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Yaroslavl.dglf" || return 1
     
}

