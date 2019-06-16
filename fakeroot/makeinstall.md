Making install in scripts
make[1]: Entering directory '/home/e/fakeroot-1.23/scripts'
sed -e 's,[@]prefix[@],/opt/fakeroot,g' -e 's,[@]bindir[@],/opt/fakeroot/bin,g' -e 's,[@]libdir[@],/opt/fakeroot/libs,g' -e 's,[@]fakeroot_transformed[@],'`echo fakeroot | sed -e 's,x,x,'`',g' -e 's,[@]faked_transformed[@],'`echo faked | sed -e 's,x,x,'`',g' -e 's,[@]signal[@],HUP,g' -e 's,[@]SHELL[@],/bin/sh,g' -e 's,[@]VERSION[@],1.23,g' -e 's,[@]DLSUFFIX[@],.so,g' -e 's,[@]LDLIBPATHVAR[@],LD_LIBRARY_PATH,g' -e 's,[@]LDPRELOADVAR[@],LD_PRELOAD,g' -e 's,[@]LDPRELOADABS[@],0,g' -e 's,[@]LDEXTRAVAR[@],,g' -e 's,[@]MACOSX_FALSE[@],,g' -e 's,[@]MACOSX_TRUE[@],#,g' < ./fakeroot.in > fakeroot
chmod +x fakeroot
make[2]: Entering directory '/home/e/fakeroot-1.23/scripts'
 /usr/bin/mkdir -p '/opt/fakeroot/bin'
 /usr/bin/install -c fakeroot '/opt/fakeroot/bin'
make[2]: Nothing to be done for 'install-data-am'.
make[2]: Leaving directory '/home/e/fakeroot-1.23/scripts'
make[1]: Leaving directory '/home/e/fakeroot-1.23/scripts'
Making install in doc
make[1]: Entering directory '/home/e/fakeroot-1.23/doc'
Making install in de
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/de'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/de'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/de/man1'
 /usr/bin/install -c -m 644 faked.1 fakeroot.1 '/opt/fakeroot/share/man/de/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/de'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/de'
Making install in es
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/es'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/es'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/es/man1'
 /usr/bin/install -c -m 644 faked.1 fakeroot.1 '/opt/fakeroot/share/man/es/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/es'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/es'
Making install in fr
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/fr'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/fr'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/fr/man1'
 /usr/bin/install -c -m 644 fakeroot.1 faked.1 '/opt/fakeroot/share/man/fr/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/fr'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/fr'
Making install in nl
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/nl'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/nl'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/nl/man1'
 /usr/bin/install -c -m 644 fakeroot.1 faked.1 '/opt/fakeroot/share/man/nl/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/nl'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/nl'
Making install in pt
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/pt'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/pt'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/pt/man1'
 /usr/bin/install -c -m 644 fakeroot.1 faked.1 '/opt/fakeroot/share/man/pt/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/pt'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/pt'
Making install in sv
make[2]: Entering directory '/home/e/fakeroot-1.23/doc/sv'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc/sv'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/sv/man1'
 /usr/bin/install -c -m 644 faked.1 fakeroot.1 '/opt/fakeroot/share/man/sv/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc/sv'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc/sv'
make[2]: Entering directory '/home/e/fakeroot-1.23/doc'
make[3]: Entering directory '/home/e/fakeroot-1.23/doc'
make[3]: Nothing to be done for 'install-exec-am'.
 /usr/bin/mkdir -p '/opt/fakeroot/share/man/man1'
 /usr/bin/install -c -m 644 faked.1 fakeroot.1 '/opt/fakeroot/share/man/man1'
make[3]: Leaving directory '/home/e/fakeroot-1.23/doc'
make[2]: Leaving directory '/home/e/fakeroot-1.23/doc'
make[1]: Leaving directory '/home/e/fakeroot-1.23/doc'
Making install in test
make[1]: Entering directory '/home/e/fakeroot-1.23/test'
make[2]: Entering directory '/home/e/fakeroot-1.23/test'
make[2]: Nothing to be done for 'install-exec-am'.
make[2]: Nothing to be done for 'install-data-am'.
make[2]: Leaving directory '/home/e/fakeroot-1.23/test'
make[1]: Leaving directory '/home/e/fakeroot-1.23/test'
make[1]: Entering directory '/home/e/fakeroot-1.23'
gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT faked.o -MD -MP -MF .deps/faked.Tpo -c -o faked.o faked.c
mv -f .deps/faked.Tpo .deps/faked.Po
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT communicate.lo -MD -MP -MF .deps/communicate.Tpo -c -o communicate.lo communicate.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT communicate.lo -MD -MP -MF .deps/communicate.Tpo -c communicate.c  -fPIC -DPIC -o .libs/communicate.o
mv -f .deps/communicate.Tpo .deps/communicate.Plo
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o libcommunicate.la  communicate.lo  -lpthread -ldl
libtool: link: ar cr .libs/libcommunicate.a .libs/communicate.o
libtool: link: ranlib .libs/libcommunicate.a
libtool: link: ( cd ".libs" && rm -f "libcommunicate.la" && ln -s "../libcommunicate.la" "libcommunicate.la" )
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o faked faked.o libcommunicate.la -lpthread -ldl
libtool: link: gcc -g -O2 -o faked faked.o  ./.libs/libcommunicate.a -lpthread -ldl
gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT simple.o -MD -MP -MF .deps/simple.Tpo -c -o simple.o simple.c
mv -f .deps/simple.Tpo .deps/simple.Po
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o simple simple.o  -lpthread -ldl
libtool: link: gcc -g -O2 -o simple simple.o  -lpthread -ldl
awk -f ./wrapawk < ./wrapfunc.inp
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT libfakeroot.lo -MD -MP -MF .deps/libfakeroot.Tpo -c -o libfakeroot.lo libfakeroot.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT libfakeroot.lo -MD -MP -MF .deps/libfakeroot.Tpo -c libfakeroot.c  -fPIC -DPIC -o .libs/libfakeroot.o
libfakeroot.c: In function ‘fts_read’:
libfakeroot.c:1953:22: warning: passing argument 1 of ‘send_get_stat64’ from incompatible pointer type [-Wincompatible-pointer-types]
     SEND_GET_STAT64(r->fts_statp, _STAT_VER);
                     ~^~~~~~~~~~~
libfakeroot.c:89:46: note: in definition of macro ‘SEND_GET_STAT64’
 #define SEND_GET_STAT64(a,b) send_get_stat64(a)
                                              ^
In file included from libfakeroot.c:60:
communicate.h:209:44: note: expected ‘struct stat64 *’ but argument is of type ‘struct stat *’
 extern void send_get_stat64(struct stat64 *buf);
                             ~~~~~~~~~~~~~~~^~~
libfakeroot.c: In function ‘fts_children’:
libfakeroot.c:1976:24: warning: passing argument 1 of ‘send_get_stat64’ from incompatible pointer type [-Wincompatible-pointer-types]
       SEND_GET_STAT64(r->fts_statp, _STAT_VER);
                       ~^~~~~~~~~~~
libfakeroot.c:89:46: note: in definition of macro ‘SEND_GET_STAT64’
 #define SEND_GET_STAT64(a,b) send_get_stat64(a)
                                              ^Making install in test
make[1]: Entering directory '/home/e/fakeroot-1.23/test'
make[2]: Entering directory '/home/e/fakeroot-1.23/test'
make[2]: Nothing to be done for 'install-exec-am'.
make[2]: Nothing to be done for 'install-data-am'.
make[2]: Leaving directory '/home/e/fakeroot-1.23/test'
make[1]: Leaving directory '/home/e/fakeroot-1.23/test'
make[1]: Entering directory '/home/e/fakeroot-1.23'
gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT faked.o -MD -MP -MF .deps/faked.Tpo -c -o faked.o faked.c
mv -f .deps/faked.Tpo .deps/faked.Po
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT communicate.lo -MD -MP -MF .deps/communicate.Tpo -c -o communicate.lo communicate.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT communicate.lo -MD -MP -MF .deps/communicate.Tpo -c communicate.c  -fPIC -DPIC -o .libs/communicate.o
mv -f .deps/communicate.Tpo .deps/communicate.Plo
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o libcommunicate.la  communicate.lo  -lpthread -ldl
libtool: link: ar cr .libs/libcommunicate.a .libs/communicate.o
libtool: link: ranlib .libs/libcommunicate.a
libtool: link: ( cd ".libs" && rm -f "libcommunicate.la" && ln -s "../libcommunicate.la" "libcommunicate.la" )
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o faked faked.o libcommunicate.la -lpthread -ldl
libtool: link: gcc -g -O2 -o faked faked.o  ./.libs/libcommunicate.a -lpthread -ldl
gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT simple.o -MD -MP -MF .deps/simple.Tpo -c -o simple.o simple.c
mv -f .deps/simple.Tpo .deps/simple.Po
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o simple simple.o  -lpthread -ldl
libtool: link: gcc -g -O2 -o simple simple.o  -lpthread -ldl
awk -f ./wrapawk < ./wrapfunc.inp
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT libfakeroot.lo -MD -MP -MF .deps/libfakeroot.Tpo -c -o libfakeroot.lo libfakeroot.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT libfakeroot.lo -MD -MP -MF .deps/libfakeroot.Tpo -c libfakeroot.c  -fPIC -DPIC -o .libs/libfakeroot.o
libfakeroot.c: In function ‘fts_read’:
libfakeroot.c:1953:22: warning: passing argument 1 of ‘send_get_stat64’ from incompatible pointer type [-Wincompatible-pointer-types]
     SEND_GET_STAT64(r->fts_statp, _STAT_VER);
                     ~^~~~~~~~~~~
libfakeroot.c:89:46: note: in definition of macro ‘SEND_GET_STAT64’
 #define SEND_GET_STAT64(a,b) send_get_stat64(a)
                                              ^
In file included from libfakeroot.c:60:
communicate.h:209:44: note: expected ‘struct stat64 *’ but argument is of type ‘struct stat *’
 extern void send_get_stat64(struct stat64 *buf);
                             ~~~~~~~~~~~~~~~^~~
libfakeroot.c: In function ‘fts_children’:
libfakeroot.c:1976:24: warning: passing argument 1 of ‘send_get_stat64’ from incompatible pointer type [-Wincompatible-pointer-types]
       SEND_GET_STAT64(r->fts_statp, _STAT_VER);
                       ~^~~~~~~~~~~
libfakeroot.c:89:46: note: in definition of macro ‘SEND_GET_STAT64’
 #define SEND_GET_STAT64(a,b) send_get_stat64(a)
                                              ^
In file included from libfakeroot.c:60:
communicate.h:209:44: note: expected ‘struct stat64 *’ but argument is of type ‘struct stat *’
 extern void send_get_stat64(struct stat64 *buf);
                             ~~~~~~~~~~~~~~~^~~
mv -f .deps/libfakeroot.Tpo .deps/libfakeroot.Plo
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2 -release 0  -o libfakeroot.la -rpath /opt/fakeroot/libs libfakeroot.lo libcommunicate.la  -lpthread -ldl
libtool: link: gcc -shared  -fPIC -DPIC  .libs/libfakeroot.o  -Wl,--whole-archive ./.libs/libcommunicate.a -Wl,--no-whole-archive  -lpthread -ldl  -g -O2   -Wl,-soname -Wl,libfakeroot-0.so -o .libs/libfakeroot-0.so
libtool: link: (cd ".libs" && rm -f "libfakeroot.so" && ln -s "libfakeroot-0.so" "libfakeroot.so")
libtool: link: ( cd ".libs" && rm -f "libfakeroot.la" && ln -s "../libfakeroot.la" "libfakeroot.la" )
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT libfakeroot_inode64.lo -MD -MP -MF .deps/libfakeroot_inode64.Tpo -c -o libfakeroot_inode64.lo libfakeroot_inode64.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT libfakeroot_inode64.lo -MD -MP -MF .deps/libfakeroot_inode64.Tpo -c libfakeroot_inode64.c  -fPIC -DPIC -o .libs/libfakeroot_inode64.o
mv -f .deps/libfakeroot_inode64.Tpo .deps/libfakeroot_inode64.Plo
/bin/sh ./libtool  --tag=CC   --mode=compile gcc -DHAVE_CONFIG_H -I.     -g -O2 -MT libfakeroot_unix2003.lo -MD -MP -MF .deps/libfakeroot_unix2003.Tpo -c -o libfakeroot_unix2003.lo libfakeroot_unix2003.c
libtool: compile:  gcc -DHAVE_CONFIG_H -I. -g -O2 -MT libfakeroot_unix2003.lo -MD -MP -MF .deps/libfakeroot_unix2003.Tpo -c libfakeroot_unix2003.c  -fPIC -DPIC -o .libs/libfakeroot_unix2003.o
mv -f .deps/libfakeroot_unix2003.Tpo .deps/libfakeroot_unix2003.Plo
/bin/sh ./libtool  --tag=CC   --mode=link gcc  -g -O2   -o libmacosx.la  libfakeroot_inode64.lo libfakeroot_unix2003.lo  -lpthread -ldl
libtool: link: ar cr .libs/libmacosx.a .libs/libfakeroot_inode64.o .libs/libfakeroot_unix2003.o
libtool: link: ranlib .libs/libmacosx.a
libtool: link: ( cd ".libs" && rm -f "libmacosx.la" && ln -s "../libmacosx.la" "libmacosx.la" )
make[2]: Entering directory '/home/e/fakeroot-1.23'
CONFIG_FILES= CONFIG_HEADERS= /bin/sh ./config.status
config.status: executing depfiles commands
config.status: executing libtool commands
 /usr/bin/mkdir -p '/opt/fakeroot/libs'
 /bin/sh ./libtool   --mode=install /usr/bin/install -c   libfakeroot.la '/opt/fakeroot/libs'
libtool: install: /usr/bin/install -c .libs/libfakeroot-0.so /opt/fakeroot/libs/libfakeroot-0.so
libtool: install: (cd /opt/fakeroot/libs && { ln -s -f libfakeroot-0.so libfakeroot.so || { rm -f libfakeroot.so && ln -s libfakeroot-0.so libfakeroot.so; }; })
libtool: install: /usr/bin/install -c .libs/libfakeroot.lai /opt/fakeroot/libs/libfakeroot.la
libtool: finish: PATH="/home/e/bin:/usr/local/sbin:/usr/local/bin:/usr/bin:/usr/lib/jvm/default/bin:/usr/bin/site_perl:/usr/bin/vendor_perl:/usr/bin/core_perl:/sbin" ldconfig -n /opt/fakeroot/libs
----------------------------------------------------------------------
Libraries have been installed in:
   /opt/fakeroot/libs

If you ever happen to want to link against installed libraries
in a given directory, LIBDIR, you must either use libtool, and
specify the full pathname of the library, or use the '-LLIBDIR'
flag during linking and do at least one of the following:
   - add LIBDIR to the 'LD_LIBRARY_PATH' environment variable
     during execution
   - add LIBDIR to the 'LD_RUN_PATH' environment variable
     during linking
   - use the '-Wl,-rpath -Wl,LIBDIR' linker flag
   - have your system administrator add LIBDIR to '/etc/ld.so.conf'

See any operating system documentation about shared libraries for
more information, such as the ld(1) and ld.so(8) manual pages.
----------------------------------------------------------------------
 /usr/bin/mkdir -p '/opt/fakeroot/bin'
  /bin/sh ./libtool   --mode=install /usr/bin/install -c faked '/opt/fakeroot/bin'
libtool: install: /usr/bin/install -c faked /opt/fakeroot/bin/faked
make[2]: Nothing to be done for 'install-data-am'.
make[2]: Leaving directory '/home/e/fakeroot-1.23'
make[1]: Leaving directory '/home/e/fakeroot-1.23'
