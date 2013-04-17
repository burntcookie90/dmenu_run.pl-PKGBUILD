pkgname=dmenu_run_perl
pkgver=1.0.0
pkgrel=2
pkgdesc='Wrapper for dmenu written in Perl. Keeps track of which commands you run most often and will always present them first'
url="http://space.rexroof.com/dmenu_run.pl.txt"
arch=('i686'  'x86_64')
depends=('dmenu' 'perl')
_common_url='http://space.rexroof.com/dmenu_run.pl.txt'

source='http://space.rexroof.com/dmenu_run.pl.txt'
md5sums=('bed3b9c6641676ae2675892f6c1de440')

package() {
	mv dmenu_run.pl.txt dmenu_run.pl
	chmod ugo+x dmenu_run.pl

	install -D -m0755 ${srcdir}/dmenu_run.pl ${pkgdir}/usr/bin/dmenu_run.pl
}
