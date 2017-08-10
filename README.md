# netcat
Openbsd netcat

requires libbsd-devel

source at: http://ftp.acc.umu.se/debian/pool/main/n/netcat-openbsd/

# instructions
git.archlinux.org/svntogit/community.git/tree/trunk/PKGBUILD?h=packages/openbsd-netcat

This is needed for .ssh/config - ProxyCommand /bin/nc -x localhost:localport %h %p
