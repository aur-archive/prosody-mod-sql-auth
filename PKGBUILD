# Maintainer: GI_Jack <iamjacksemail@hackermail.com>

pkgname=prosody-mod-sql-auth
pkgver=20140303
pkgrel=2
pkgdesc="Add support for authenticating with SQL in prosody"
arch=('any')
url="http://code.google.com/p/prosody-modules/wiki/mod_auth_sql"
license=('MIT')
depends=('prosody' 'lua51-dbi')
source=("https://prosody-modules.googlecode.com/hg-history/1b55d8f86644730adaca3faf25363adaefe156ac/mod_auth_sql/mod_auth_sql.lua")
sha1sums=('8ebf544e80fd105764d254ac7ffd8302bad561d5')
package() {
  install -Dm 644 "mod_auth_sql.lua" "${pkgdir}/usr/lib/prosody/modules/mod_auth_sql.lua"
}

