                        Debian worldwide mirror sites
                        -----------------------------

Debian is distributed (mirrored) on hundreds of servers on the Internet.
Using a nearby server will probably speed up your download, and also
reduce the load on our central servers and on the Internet as a whole.

Debian mirrors can be primary and secondary. The definitions are as follows:

  A primary mirror site has good bandwidth, is available 24 hours a day,
  and has an easy to remember name of the form ftp.<country>.debian.org.
  They are all automatically updated whenever there are updates to
  the Debian archive.

  A secondary mirror site may have restrictions on what they mirror (due to
  space restrictions). Just because a site is secondary doesn't necessarily
  mean it'll be any slower or less up to date than a primary site.

Use the site closest to you for the fastest downloads possible whether it is
a primary or secondary site. The program `netselect' can be used to
determine the site with the least latency; use a download program such as
`wget' or `rsync' for determining the site with the most throughput.
Note that geographic proximity often isn't the most important factor for
determining which machine will serve you best.

The authoritative copy of the following list can always be found at:
                      http://www.debian.org/mirror/list
If you know of any mirrors that are missing from this list,
please have the site maintainer fill out the form at:
                     http://www.debian.org/mirror/submit
Everything else you want to know about Debian mirrors:
                        http://www.debian.org/mirror/


                         Primary Debian mirror sites
                         ---------------------------

 Country         Site                  Debian archive  Architectures
 ---------------------------------------------------------------------------
<<<<<<< HEAD
 Austria         ftp.at.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Australia       ftp.au.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Belgium         ftp.be.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Bulgaria        ftp.bg.debian.org     /debian/        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
 Brazil          ftp.br.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Canada          ftp.ca.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Switzerland     ftp.ch.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Chile           ftp.cl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Czech Republic  ftp.cz.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Germany         ftp.de.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Germany         ftp2.de.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Denmark         ftp.dk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Estonia         ftp.ee.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Spain           ftp.es.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Finland         ftp.fi.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 France          ftp.fr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 France          ftp2.fr.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Great Britain   ftp.uk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Greece          ftp.gr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Hong Kong       ftp.hk.debian.org     /debian/        alpha amd64 arm armel i386 ia64 powerpc sparc
 Croatia         ftp.hr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Hungary         ftp.hu.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Ireland         ftp.ie.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Iceland         ftp.is.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Italy           ftp.it.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Japan           ftp.jp.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Japan           ftp2.jp.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Korea           ftp.kr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Mexico          ftp.mx.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Netherlands     ftp.nl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Norway          ftp.no.debian.org     /debian/        amd64 arm armel i386 ia64 powerpc sparc
 New Zealand     ftp.nz.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Poland          ftp.pl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Portugal        ftp.pt.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Romania         ftp.ro.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Russia          ftp.ru.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Sweden          ftp.se.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Slovenia        ftp.si.debian.org     /debian/        alpha amd64 i386 ia64 m68k powerpc sparc
 Slovakia        ftp.sk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Turkey          ftp.tr.debian.org     /debian/        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Taiwan          ftp.tw.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 United States   ftp.us.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
 Austria         ftp.at.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Australia       ftp.au.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Bosnia & Herzegovina  ftp.ba.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
 Belgium         ftp.be.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Bulgaria        ftp.bg.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Brazil          ftp.br.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Canada          ftp.ca.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Switzerland     ftp.ch.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Chile           ftp.cl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Czech Republic  ftp.cz.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Germany         ftp.de.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Germany         ftp2.de.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Denmark         ftp.dk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Estonia         ftp.ee.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Spain           ftp.es.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Finland         ftp.fi.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 France          ftp.fr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 France          ftp2.fr.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Great Britain   ftp.uk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Greece          ftp.gr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Hong Kong       ftp.hk.debian.org     /debian/        alpha amd64 arm armel i386 ia64 powerpc sparc
 Croatia         ftp.hr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Hungary         ftp.hu.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Ireland         ftp.ie.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Iceland         ftp.is.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Italy           ftp.it.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Japan           ftp.jp.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Japan           ftp2.jp.debian.org    /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Korea           ftp.kr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Mexico          ftp.mx.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Netherlands     ftp.nl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Norway          ftp.no.debian.org     /debian/        amd64 i386 ia64 powerpc sparc
 New Zealand     ftp.nz.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Poland          ftp.pl.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Portugal        ftp.pt.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Romania         ftp.ro.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Russia          ftp.ru.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Sweden          ftp.se.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Slovenia        ftp.si.debian.org     /debian/        amd64 i386 powerpc sparc
 Slovakia        ftp.sk.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Turkey          ftp.tr.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Taiwan          ftp.tw.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 Ukraine         ftp.ua.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
 United States   ftp.us.debian.org     /debian/        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream


                   Secondary mirrors of the Debian archive
                   ---------------------------------------

HOST NAME                       FTP                             HTTP                            ARCHITECTURES
---------                       ---                             ----                            -------------

AR Argentina
------------
debian.logiclinux.com                                           /debian/                        amd64 i386
ftp.ccc.uba.ar                  /pub/linux/debian/debian/       /pub/linux/debian/debian/       amd64 i386
<<<<<<< HEAD
debian.torredehanoi.org         /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc

AT Austria
----------
ftp.at.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.sil.at)
gd.tuwien.ac.at                 /opsys/linux/debian/            /opsys/linux/debian/            alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mur.at                   /debian/                        /debian/                        amd64 i386 ia64
ftp.tu-graz.ac.at               /mirror/debian/                 /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.univie.ac.at                /systems/linux/debian/debian/   /systems/linux/debian/debian/   i386
debian.inode.at                 /debian/                        /debian/                        alpha amd64 arm armel i386 powerpc sparc
esda.wu-wien.ac.at              /pub/debian/                                                    amd64 i386 powerpc

AU Australia
------------
ftp.au.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (mirror.linux.org.au)
mirror.aarnet.edu.au            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.monash.edu.au               /pub/linux/debian/              /pub/linux/debian/              amd64 i386
ftp.uwa.edu.au                  /debian/                        /debian/                        amd64 i386
mirror.eftel.com                /debian/                        /debian/                        amd64 i386
mirror.pacific.net.au           /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.planetmirror.com                                         /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.iinet.net.au                /debian/debian/                 /debian/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.optus.net                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.cse.unsw.edu.au          /debian/                        /debian/                        amd64 i386 ia64 powerpc
mirror.3fl.net.au               /pub/debian/                    /debian/                        amd64 i386
ftp.netspace.net.au             /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc

BE Belgium
----------
ftp.be.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.belnet.be)
ftp.kulnet.kuleuven.ac.be       /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.easynet.be                  /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.debian.skynet.be            /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.scarlet.be                  /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.be.gbxs.net              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

BG Bulgaria
-----------
ftp.bg.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.spnet.net)
debian.ludost.net               /debian/                        /debian/                        i386
ftp.uni-sofia.bg                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.telecoms.bg              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mnet.bg                  /debian/                        /debian/                        i386
debian.networx-bg.com           /debian/                        /debian/                        amd64 i386

BR Brazil
---------
ftp.br.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.c3sl.ufpr.br)
debian.das.ufsc.br              /pub/debian/                                                    amd64 i386
download.unesp.br                                               /linux/debian/                  alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
sft.if.usp.br                                                   /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
debian.torredehanoi.org         /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc

AT Austria
----------
ftp.at.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.sil.at)
gd.tuwien.ac.at                 /opsys/linux/debian/            /opsys/linux/debian/            alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mur.at                   /debian/                        /debian/                        amd64 i386 ia64
ftp.tu-graz.ac.at               /mirror/debian/                 /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.univie.ac.at                /systems/linux/debian/debian/   /systems/linux/debian/debian/   i386
debian.inode.at                 /debian/                        /debian/                        alpha amd64 arm armel i386 powerpc sparc
debian.lagis.at                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

AU Australia
------------
ftp.au.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (mirror.linux.org.au)
mirror.aarnet.edu.au            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.monash.edu.au               /pub/linux/debian/              /pub/linux/debian/              amd64 i386
ftp.uwa.edu.au                  /debian/                        /debian/                        amd64 i386
mirror.eftel.com                /debian/                        /debian/                        amd64 i386
mirror.pacific.net.au           /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.iinet.net.au                /debian/debian/                 /debian/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.optus.net                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.cse.unsw.edu.au          /debian/                        /debian/                        amd64 i386 ia64 powerpc
mirror.3fl.net.au               /pub/debian/                    /debian/                        amd64 i386
ftp.netspace.net.au             /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc

BA Bosnia & Herzegovina
-----------------------
ftp.ba.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (mirror.debian.com.ba)

BE Belgium
----------
ftp.be.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.belnet.be)
ftp.kulnet.kuleuven.ac.be       /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.easynet.be                  /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.debian.skynet.be            /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.be.gbxs.net              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

BG Bulgaria
-----------
ftp.bg.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.spnet.net)
debian.ludost.net               /debian/                        /debian/                        i386
ftp.uni-sofia.bg                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.telecoms.bg              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mnet.bg                  /debian/                        /debian/                        i386
debian.networx-bg.com           /debian/                        /debian/                        amd64 armel i386

BR Brazil
---------
ftp.br.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.c3sl.ufpr.br)
debian.das.ufsc.br              /pub/debian/                                                    amd64 i386
download.unesp.br                                               /linux/debian/                  alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc
sft.if.usp.br                                                   /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
linorg.usp.br                   /debian/                        /debian/                        i386
linux.iq.usp.br                                                 /debian/                        amd64 i386
ftp.pucpr.br                    /debian/                                                        amd64 hurd-i386 i386
debian.las.ic.unicamp.br        /debian/                        /debian/                        amd64 i386 powerpc sparc
<<<<<<< HEAD
debian.pop-sc.rnp.br                                            /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

BY Belarus
----------
linux.org.by                    /debian/                        /debian/                        amd64 i386
=======
debian.pop-sc.rnp.br                                            /debian/                        amd64 i386

BY Belarus
----------
linux.org.by                                                    /debian/                        amd64 i386
>>>>>>> upstream
ftp.mgts.by                     /debian/                        /debian/                        amd64 i386

CA Canada
---------
<<<<<<< HEAD
ftp.ca.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.yorku.ca                                                 /debian/                        amd64 i386
ftp3.nrc.ca                     /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
gulus.usherbrooke.ca            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.cpsc.ucalgary.ca         /mirror/debian.org/debian/      /mirror/debian.org/debian/      amd64 i386
mirror.peer1.net                                                /debian/                        alpha amd64 arm armel i386 mips mipsel powerpc sparc
debian.mirror.rafal.ca          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.savoirfairelinux.net     /debian/                        /debian/                        amd64 i386 powerpc
debian.mirror.iweb.ca           /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.publicns.net             /pub/debian/                    /pub/debian/                    amd64 i386
mirror.csclub.uwaterloo.ca      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

CH Switzerland
--------------
ftp.ch.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.ethz.ch)
mirror.switch.ch                /mirror/debian/                 /ftp/mirror/debian/             alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.ca.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.yorku.ca                                                 /debian/                        amd64 i386
ftp3.nrc.ca                     /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
gulus.usherbrooke.ca            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.cpsc.ucalgary.ca         /debian/                        /mirror/debian.org/debian/      alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.peer1.net                                                /debian/                        amd64 i386
debian.mirror.rafal.ca          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.savoirfairelinux.net     /debian/                        /debian/                        amd64 i386 powerpc
debian.mirror.iweb.ca           /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.publicns.net             /pub/debian/                    /pub/debian/                    amd64 armel i386
mirror.csclub.uwaterloo.ca      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

CH Switzerland
--------------
ftp.ch.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.ethz.ch)
mirror.switch.ch                /mirror/debian/                 /ftp/mirror/debian/             alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
debian.csg.uzh.ch                                               /debian/                        amd64 i386

CL Chile
--------
<<<<<<< HEAD
ftp.cl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.cl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
  (debian.ciencias.uchile.cl)
debian.ubiobio.cl                                               /debian/                        amd64 i386 powerpc
debian.utalca.cl                                                /debian/                        amd64 i386
mirror.debian.cl                                                /debian/                        amd64 i386
<<<<<<< HEAD

CN China
--------
ftp.linuxforum.net              /debian/                                                        i386
mirrors.geekbone.org            /debian/                        /debian/                        alpha amd64 hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.cn99.com                 /debian/                        /debian/                        amd64 i386
www.anheng.com.cn               /debian/                        /debian/                        alpha amd64 arm hppa i386 ia64 mips mipsel powerpc s390 sparc

CZ Czech Republic
-----------------
ftp.cz.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.debian.cz)
debian.sh.cvut.cz               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.zcu.cz                      /mirrors/debian/                /mirrors/debian/                amd64 i386
debian.mirror.web4u.cz          /                               /                               amd64 i386

DE Germany
----------
ftp.de.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.inf.tu-dresden.de)
ftp2.de.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.rfc822.org)
ftp.tu-clausthal.de             /pub/linux/debian/                                              amd64 arm armel i386 ia64 m68k mips powerpc sparc
debian.uni-essen.de             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.freenet.de                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.informatik.rwth-aachen.de   /pub/Linux/debian/              /ftp/pub/Linux/debian/          alpha amd64 i386 powerpc sparc
ftp-stud.fht-esslingen.de       /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.stw-bonn.de                 /debian/                        /debian/                        amd64 i386
ftp.fu-berlin.de                /pub/unix/linux/mirrors/debian/                                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.tu-bs.de                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.uni-koeln.de                /debian/                        /debian/                        alpha amd64 i386 powerpc sparc
ftp.mpi-sb.mpg.de               /pub/linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.tiscali.de                  /pub/debian/debian/             /pub/debian/debian/             amd64 arm armel hurd-i386 i386 ia64
ftp.tu-chemnitz.de              /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.uni-kl.de                   /debian/                        /debian/                        amd64 i386 ia64 powerpc sparc
ftp.uni-bayreuth.de             /pub/linux/Debian/debian/       /linux/Debian/debian/           alpha amd64 hurd-i386 i386 ia64
ftp.informatik.hu-berlin.de     /pub/Linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp5.gwdg.de                    /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.hosteurope.de               /pub/linux/debian/              /pub/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.informatik.uni-frankfurt.de /pub/Mirrors/debian.org/debian/ /debian/                        amd64 i386 ia64 powerpc
debian.netcologne.de            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
artfiles.org                    /debian/                        /debian/                        amd64 i386
debian.intergenia.de                                            /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.cruisix.net              /debian/                        /debian/                        amd64 i386 powerpc
ftp.rrzn.uni-hannover.de        /debian/debian/                                                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.charite.de                                               /debian/                        i386
ftp.plusline.de                 /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
sinclair.farm.ftbfs.de                                          /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

DK Denmark
----------
ftp.dk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (mirrors.dotsrc.org)
ftp.dkuug.dk                    /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.here.dk                  /debian/                        /debian/                        amd64 i386 ia64 mips powerpc
debian.uni-c.dk                                                 /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirrors.telianet.dk             /debian/                        /debian/                        amd64 i386 powerpc sparc

EE Estonia
----------
ftp.ee.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.aso.ee)
ftp.linux.ee                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

ES Spain
--------
ftp.es.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ulises.hostalia.com)
ftp.rediris.es                  /debian/                        /debian/                        alpha amd64 i386 ia64 powerpc sparc
ftp.cica.es                     /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.caliu.cat                   /debian/                        /debian/                        amd64 i386 ia64 powerpc
ftp.gva.es                                                      /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.gul.uc3m.es                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.um.es                       /mirror/debian/                                                 i386
jane.uab.cat                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.udc.es                      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.grn.cat                  /debian/                        /debian/                        amd64 i386 ia64 powerpc
debian.com.es                   /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc

FI Finland
----------
ftp.fi.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (trumpetti.atm.tut.fi)
ftp.funet.fi                    /pub/linux/mirrors/debian/      /pub/linux/mirrors/debian/      alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.jyu.fi                      /debian/                        /debian/                        alpha amd64 hurd-i386 i386 powerpc sparc

FR France
---------
ftp.fr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.proxad.net)
ftp2.fr.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.oleane.net)
ftp.iut-bm.univ-fcomte.fr       /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.eudil.fr                    /debian/                        /debian/                        alpha arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.proxad.net                  /mirrors/ftp.debian.org/                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.lip6.fr                     /pub/linux/distributions/debian//pub/linux/distributions/debian/amd64 i386
debian.ens-cachan.fr            /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.u-picardie.fr               /mirror/debian/                 /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mirrors.easynet.fr       /debian/                        /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.u-strasbg.fr                /debian/                        /debian/                        alpha amd64 hurd-i386 i386 ia64 m68k powerpc sparc
debian.ibisc.univ-evry.fr       /debian/                        /debian/                        amd64 i386
debian.cict.fr                  /debian/                        /debian/                        amd64 arm armel hurd-i386 i386
mir1.ovh.net                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mir2.ovh.net                                                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.nerim.net                   /debian/                        /debian/                        i386
ftp.crihan.fr                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mines.inpl-nancy.fr      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.debian.ikoula.com           /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
webb.ens-cachan.fr              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirrors.ircam.fr                /pub/debian/                    /pub/debian/                    alpha amd64 hurd-i386 i386 ia64 m68k mips mipsel powerpc sparc
debian.mirror.inra.fr           /debian/                        /debian/                        amd64 arm armel i386 ia64 powerpc sparc
debian.med.univ-tours.fr        /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.univ-pau.fr                 /pub/mirrors/debian/            /linux/mirrors/debian/          amd64 i386
ftp.univ-nantes.fr              /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirrors.compuscene.org                                          /debian/                        i386
debian.revolsys.fr              /debian/                        /debian/                        amd64 i386
=======
debian.netlinux.cl              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390

CN China
--------
mirrors.geekbone.org            /debian/                        /debian/                        alpha amd64 hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
www.anheng.com.cn               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

CZ Czech Republic
-----------------
ftp.cz.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.debian.cz)
debian.sh.cvut.cz               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.zcu.cz                      /mirrors/debian/                /mirrors/debian/                amd64 i386
debian.mirror.web4u.cz          /                               /                               amd64 i386
ftp.cvut.cz                     /debian/                        /debian/                        amd64 i386 ia64
debian.ignum.cz                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mirror.dkm.cz            /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

DE Germany
----------
ftp.de.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.inf.tu-dresden.de)
ftp2.de.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.rfc822.org)
ftp.tu-clausthal.de             /pub/linux/debian/                                              amd64 arm armel i386 ia64 mips powerpc sparc
debian.uni-duisburg-essen.de    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.freenet.de                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.informatik.rwth-aachen.de   /pub/Linux/debian/              /ftp/pub/Linux/debian/          alpha amd64 i386 powerpc sparc
ftp-stud.fht-esslingen.de       /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.stw-bonn.de                 /debian/                        /debian/                        amd64 i386
ftp.fu-berlin.de                /pub/unix/linux/mirrors/debian/                                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.tu-bs.de                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.uni-koeln.de                /debian/                        /debian/                        alpha amd64 i386 powerpc sparc
ftp.mpi-sb.mpg.de               /pub/linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.tu-chemnitz.de              /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.uni-kl.de                   /debian/                        /debian/                        amd64 i386 ia64 powerpc sparc
ftp.uni-bayreuth.de             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.informatik.hu-berlin.de     /pub/Linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp5.gwdg.de                    /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.hosteurope.de               /pub/linux/debian/              /pub/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.informatik.uni-frankfurt.de /pub/Mirrors/debian.org/debian/ /debian/                        amd64 i386 ia64 powerpc
debian.netcologne.de            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
artfiles.org                    /debian/                        /debian/                        amd64 i386
debian.intergenia.de                                            /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.cruisix.net              /debian/                        /debian/                        amd64 i386 powerpc
ftp.rrzn.uni-hannover.de        /debian/debian/                                                 amd64 i386 ia64
debian.charite.de                                               /debian/                        i386
ftp.plusline.de                 /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.ayous.org                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.morphium.info            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

DK Denmark
----------
ftp.dk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (mirrors.dotsrc.org)
ftp.dkuug.dk                    /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.uni-c.dk                                                 /debian/                        alpha amd64 i386 ia64 powerpc
mirrors.telianet.dk             /debian/                        /debian/                        amd64 i386 powerpc sparc
debianmirror.wwi.dk                                             /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

EE Estonia
----------
ftp.ee.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.aso.ee)

ES Spain
--------
ftp.es.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.gul.uc3m.es)
ftp.rediris.es                  /debian/                        /debian/                        alpha amd64 i386 ia64 powerpc sparc
ftp.cica.es                     /debian/                        /debian/                        amd64 i386 ia64 powerpc
ftp.caliu.cat                   /debian/                        /debian/                        amd64 armel i386 ia64 powerpc
ftp.gva.es                      /mirror/debian/                 /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.um.es                       /mirror/debian/                                                 i386
ftp.udc.es                      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.grn.cat                  /debian/                        /debian/                        amd64 i386 ia64 powerpc
debian.com.es                                                   /debian/                        alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc

FI Finland
----------
ftp.fi.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (trumpetti.atm.tut.fi)
ftp.funet.fi                    /pub/linux/mirrors/debian/      /pub/linux/mirrors/debian/      alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.jyu.fi                      /debian/                        /debian/                        alpha amd64 hurd-i386 i386 powerpc sparc
ftp.seclan.com                  /debian/                        /debian/                        amd64 i386 powerpc

FR France
---------
ftp.fr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.proxad.net)
ftp2.fr.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.oleane.net)
ftp.iut-bm.univ-fcomte.fr       /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.eudil.fr                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.proxad.net                  /mirrors/ftp.debian.org/                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.lip6.fr                     /pub/linux/distributions/debian//pub/linux/distributions/debian/amd64 i386
debian.ens-cachan.fr            /debian/                        /ftp/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.u-picardie.fr               /mirror/debian/                 /mirror/debian/                 alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mirrors.easynet.fr       /debian/                        /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.u-strasbg.fr                /debian/                        /debian/                        alpha amd64 armel hurd-i386 i386 ia64 powerpc sparc
debian.cict.fr                  /debian/                        /debian/                        amd64 arm armel hurd-i386 i386
mir1.ovh.net                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mir2.ovh.net                                                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.nerim.net                   /debian/                        /debian/                        i386
ftp.crihan.fr                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mines.inpl-nancy.fr      /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
webb.ens-cachan.fr              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirrors.ircam.fr                /pub/debian/                    /pub/debian/                    alpha amd64 hurd-i386 i386 ia64 mips mipsel powerpc sparc
debian.mirror.inra.fr           /debian/                        /debian/                        amd64 arm armel i386 ia64 powerpc sparc
debian.med.univ-tours.fr        /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc
ftp.univ-pau.fr                 /pub/mirrors/debian/            /linux/mirrors/debian/          amd64 i386
ftp.univ-nantes.fr              /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirrors.compuscene.org                                          /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
debian.univ-reims.fr            /debian/                        /debian/                        amd64 i386

GB Great Britain
----------------
<<<<<<< HEAD
ftp.uk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.hands.com)
debian.man.ac.uk                                                /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
www.mirrorservice.org           /sites/ftp.debian.org/debian/   /sites/ftp.debian.org/debian/   alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.ticklers.org                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.virginmedia.com          /pub/debian/                    /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.positive-internet.com    /debian/                        /debian/                        amd64 hppa i386 ia64 powerpc
the.earth.li                    /debian/                        /debian/                        amd64 hurd-i386 i386
ukdebian.mirror.anlx.net        /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.ox.ac.uk                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.zetnet.co.uk             /debian/                        /debian/                        amd64 i386 mipsel
=======
ftp.uk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.hands.com)
debian.man.ac.uk                                                /debian/                        amd64 hurd-i386 i386
www.mirrorservice.org           /sites/ftp.debian.org/debian/   /sites/ftp.debian.org/debian/   alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.ticklers.org                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.virginmedia.com          /mirrors/ftp.debian.org         /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.positive-internet.com    /debian/                        /debian/                        amd64 hppa i386 ia64 powerpc sparc
the.earth.li                    /debian/                        /debian/                        amd64 hurd-i386 i386
ukdebian.mirror.anlx.net        /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.ox.ac.uk                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.zetnet.co.uk             /debian/                        /debian/                        amd64 i386 mipsel
mirror.sov.uk.goscomb.net       /debian/                        /debian/                        amd64 i386
>>>>>>> upstream

GE Georgia
----------
ftp.ifg.gtu.ge                  /debian/                                                        amd64 i386

GR Greece
---------
<<<<<<< HEAD
ftp.gr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.ntua.gr)
debian.otenet.gr                /pub/linux/debian/              /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.duth.gr                     /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.softnet.tuc.gr              /pub/linux/debian/              /ftp/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.cc.uoc.gr                   /mirrors/linux/debian/          /mirrors/linux/debian/          alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
postmortem.csd.auth.gr                                          /debian/                        amd64 i386
ftp.ceid.upatras.gr             /pub/debian/                    /pub/debian/                    alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.gr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.ntua.gr)
debian.otenet.gr                /pub/linux/debian/              /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.duth.gr                     /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.softnet.tuc.gr                                              /ftp/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.cc.uoc.gr                   /mirrors/linux/debian/          /mirrors/linux/debian/          alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream

HK Hong Kong
------------
ftp.hk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel i386 ia64 powerpc sparc
<<<<<<< HEAD
www.zentek-international.com                                    /mirrors/debian/                alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

HR Croatia
----------
ftp.hr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.carnet.hr)
ftp.irb.hr                      /debian/                        /debian/                        alpha amd64 arm armel hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.carnet.hr                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======

HR Croatia
----------
ftp.hr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.carnet.hr)
ftp.irb.hr                      /debian/                        /debian/                        alpha amd64 arm armel hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.carnet.hr                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
debian.iskon.hr                 /debian/                        /debian/                        amd64 hurd-i386 i386 ia64 s390

HU Hungary
----------
<<<<<<< HEAD
ftp.hu.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.fsn.hu)
ftp.kfki.hu                     /pub/linux/debian/              /linux/debian/                  alpha arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.externet.hu                 /debian/                        /debian/                        amd64 i386
ftp.bme.hu                      /OS/Linux/dist/debian/          /OS/Linux/dist/debian/          amd64 hurd-i386 i386 ia64
debian.mirrors.crysys.hu        /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.hu.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.fsn.hu)
ftp.kfki.hu                     /pub/linux/debian/              /linux/debian/                  alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.bme.hu                      /OS/Linux/dist/debian/          /OS/Linux/dist/debian/          amd64 hurd-i386 i386 ia64
debian.mirrors.crysys.hu        /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
debian.sth.sze.hu               /debian/                        /                               amd64 i386 ia64

ID Indonesia
------------
kebo.vlsm.org                   /debian/                        /debian/                        amd64 hurd-i386 i386 powerpc
<<<<<<< HEAD
debian.indika.net.id                                            /debian/                        i386

IE Ireland
----------
ftp.ie.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.heanet.ie)
ftp.esat.net                    /pub/linux/debian/              /pub/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

IL Israel
---------
mirror.inter.net.il             /pub/debian/                    /pub/debian/                    amd64 i386 sparc
=======
mirror.unej.ac.id               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

IE Ireland
----------
ftp.ie.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.heanet.ie)
ftp.esat.net                    /pub/linux/debian/              /pub/linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

IL Israel
---------
>>>>>>> upstream
debian.co.il                                                    /debian/                        i386
mirror.isoc.org.il                                              /pub/debian/                    amd64 i386

IN India
--------
ftp.iitm.ac.in                  /debian/                        /debian/                        amd64 i386

IS Iceland
----------
<<<<<<< HEAD
ftp.is.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.is.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
  (ftp.rhnet.is)

IT Italy
--------
<<<<<<< HEAD
ftp.it.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.bofh.it)
giano.com.dist.unige.it         /debian/                        /debian/                        amd64 arm armel i386
ftp.bononia.it                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
freedom.dicea.unifi.it          /pub/linux/debian/              /ftp/pub/linux/debian/          amd64 hurd-i386 i386
ftp.eutelia.it                  /pub/Debian_Mirror/                                             alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mi.mirror.garr.it               /mirrors/debian/                /mirrors/debian/                alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.fastweb.it               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.unina.it                    /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.fastbull.org             /debian/                        /debian/                        amd64 i386 powerpc sparc
debian.dynamica.it              /debian/                        /debian/                        amd64 hurd-i386 i386 ia64 powerpc
mirror.units.it                                                 /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

JP Japan
--------
ftp2.jp.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.debian.or.jp)
ftp.jp.debian.org                                               /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (dennou-q.gfd-dennou.org, dennou-k.gfd-dennou.org, dennou-h.gfd-dennou.org, debian.topstudio.co.jp, www.oyu-net.jp, hanzubon.jp, ftp.nara.wide.ad.jp, ftp2.jp.debian.org)
ftp.nara.wide.ad.jp             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ring.asahi-net.or.jp            /pub/linux/debian/debian/       /archives/linux/debian/debian/  alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.dti.ad.jp                   /pub/Linux/debian/              /pub/Linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
dennou-k.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
dennou-q.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.yz.yamagata-u.ac.jp         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
sb.itc.u-tokyo.ac.jp            /DEBIAN/                        /DEBIAN/                        amd64 hurd-i386 i386 powerpc
ftp.riken.jp                    /pub/Linux/debian/debian/       /pub/Linux/debian/debian/       amd64 i386
debian.shimpinomori.net                                         /debian/                        amd64 i386 powerpc
www.ring.gr.jp                  /pub/linux/debian/debian/       /archives/linux/debian/debian/  alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.jaist.ac.jp                 /pub/Linux/Debian/              /pub/Linux/Debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
www.cohsoft.com                                                 /debian/                        amd64 hurd-i386 i386 powerpc
dennou-h.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

KR Korea
--------
ftp.kr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.kaist.ac.kr)
ftp.daum.net                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

LT Lithuania
------------
ameba.sc-uni.ktu.lt             /debian/                        /debian/                        amd64 i386
=======
ftp.it.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.bofh.it)
giano.com.dist.unige.it         /debian/                        /debian/                        amd64 arm armel i386
ftp.bononia.it                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
freedom.dicea.unifi.it          /pub/linux/debian/              /ftp/pub/linux/debian/          amd64 hurd-i386 i386
mi.mirror.garr.it               /mirrors/debian/                /mirrors/debian/                alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.fastweb.it               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.unina.it                    /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.fastbull.org             /debian/                        /debian/                        amd64 i386 powerpc
debian.dynamica.it              /debian/                        /debian/                        amd64 hurd-i386 i386 ia64 powerpc
mirror.units.it                                                 /debian/                        amd64 i386

JP Japan
--------
ftp2.jp.debian.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.debian.or.jp)
ftp.jp.debian.org                                               /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (dennou-q.gfd-dennou.org, dennou-k.gfd-dennou.org, dennou-h.gfd-dennou.org, debian.topstudio.co.jp, www.oyu-net.jp, hanzubon.jp, ftp.nara.wide.ad.jp, ftp2.jp.debian.org)
ftp.nara.wide.ad.jp             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.dti.ad.jp                   /pub/Linux/debian/              /pub/Linux/debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
dennou-k.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
dennou-q.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.yz.yamagata-u.ac.jp         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
sb.itc.u-tokyo.ac.jp            /DEBIAN/                        /DEBIAN/                        amd64 hurd-i386 i386 powerpc
ftp.riken.jp                    /Linux/debian/debian/           /Linux/debian/debian/           alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.shimpinomori.net                                         /debian/                        amd64 i386 powerpc
ftp.jaist.ac.jp                 /pub/Linux/Debian/              /pub/Linux/Debian/              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
www.cohsoft.com                                                 /debian/                        amd64 hurd-i386 i386 powerpc
dennou-h.gfd-dennou.org         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

KR Korea
--------
ftp.kr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.kaist.ac.kr)
ftp.daum.net                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

LT Lithuania
------------
ftp.litnet.lt                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
>>>>>>> upstream
debian.balt.net                 /debian/                        /debian/                        amd64 arm armel i386 sparc

LV Latvia
---------
koyanet.lv                      /debian/                        /debian/                        amd64 i386

MT Malta
--------
<<<<<<< HEAD
debian.eng.um.edu.mt                                            /debian/                        i386

MX Mexico
---------
ftp.mx.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.unam.mx)
mmc.igeofcu.unam.mx                                             /debian/                        amd64 hurd-i386 i386 ia64
=======
debian.eng.um.edu.mt                                            /debian/                        amd64 i386

MX Mexico
---------
ftp.mx.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.unam.mx)
mmc.geofisica.unam.mx           /debian/                        /debian/                        amd64 hurd-i386 i386 ia64

NC New Caledonia
----------------
debian.nautile.nc               /debian/                        /debian/                        amd64 arm i386
>>>>>>> upstream

NI Nicaragua
------------
debian.uni.edu.ni                                               /debian/                        amd64 hurd-i386 i386

NL Netherlands
--------------
<<<<<<< HEAD
ftp.nl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.snt.utwente.nl)
ftp.nluug.nl                    /pub/os/Linux/distr/debian/     /pub/os/Linux/distr/debian/     alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.surfnet.nl                  /pub/os/Linux/distr/debian/     /os/Linux/distr/debian/         alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.debian.nl                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.tiscali.nl                  /pub/mirrors/debian/            /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

NO Norway
---------
ftp.no.debian.org               /debian/                        /debian/                        amd64 arm armel i386 ia64 powerpc sparc
=======
ftp.nl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.snt.utwente.nl)
ftp.nluug.nl                    /pub/os/Linux/distr/debian/     /pub/os/Linux/distr/debian/     alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.surfnet.nl                  /pub/os/Linux/distr/debian/     /os/Linux/distr/debian/         alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.debian.nl                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.tiscali.nl                  /pub/mirrors/debian/            /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

NO Norway
---------
ftp.no.debian.org               /debian/                        /debian/                        amd64 i386 ia64 powerpc sparc
>>>>>>> upstream
  (ftp.uninett.no)

NZ New Zealand
--------------
<<<<<<< HEAD
ftp.nz.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.citylink.co.nz)
debian.ihug.co.nz               /debian/                        /debian/                        amd64 i386

PL Poland
---------
ftp.pl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.task.gda.pl)
ftp.icm.edu.pl                  /pub/Linux/debian/              /pub/Linux/debian/              alpha amd64 hurd-i386 i386 sparc
ftp.ps.pl                       /pub/Linux/debian/              /pub/Linux/debian/              amd64 i386
ftp.man.szczecin.pl             /pub/Linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.vectranet.pl                /debian/                        /debian/                        amd64 i386
ftp.pwr.wroc.pl                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.man.poznan.pl               /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.sileman.pl                  /pub/debian/                                                    amd64 hurd-i386 i386 ia64
=======
ftp.nz.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.citylink.co.nz)

PF French Polynesia
-------------------
repository.linux.pf             /debian/                        /debian/                        amd64 i386

PL Poland
---------
ftp.pl.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.task.gda.pl)
ftp.icm.edu.pl                  /pub/Linux/debian/              /pub/Linux/debian/              alpha amd64 hurd-i386 i386 powerpc sparc
ftp.man.szczecin.pl             /pub/Linux/debian/                                              alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.vectranet.pl                /debian/                        /debian/                        amd64 i386
ftp.pwr.wroc.pl                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.man.poznan.pl               /pub/linux/debian/debian/       /pub/linux/debian/debian/       alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
piotrkosoft.net                 /pub/mirrors/debian/            /pub/mirrors/debian/            amd64 i386

PT Portugal
-----------
<<<<<<< HEAD
ftp.pt.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.uevora.pt)
ftp.eq.uc.pt                    /pub/software/Linux/debian/     /software/Linux/debian/         alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.ua.pt                    /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.linux.pt                    /pub/mirrors/debian/            /pub/mirrors/debian/            amd64 hurd-i386 i386
ftp.telepac.pt                  /pub/debian/                                                    amd64 i386 sparc
mirrors.nfsi.pt                 /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
neacm.fe.up.pt                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
cesium.di.uminho.pt             /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.netvisao.pt              /debian/                        /                               alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.dcc.fc.up.pt                                             /debian/                        amd64 i386 ia64 powerpc

RO Romania
----------
ftp.ro.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.pt.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.uevora.pt)
ftp.eq.uc.pt                    /pub/software/Linux/debian/     /software/Linux/debian/         alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.ua.pt                    /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirrors.nfsi.pt                 /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
neacm.fe.up.pt                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
cesium.di.uminho.pt             /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.netvisao.pt              /debian/                        /                               alpha amd64 arm hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.dcc.fc.up.pt                                             /debian/                        amd64 i386 ia64 powerpc
mirror.sim.ul.pt                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

RO Romania
----------
ftp.ro.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
  (ftp.iasi.roedu.net)
ftp.lug.ro                      /debian/                        /debian/                        amd64 i386 powerpc
ftp.mikesnet.ro                 /debian/                        /debian/                        amd64 i386 mips mipsel

RU Russia
---------
<<<<<<< HEAD
ftp.ru.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.chg.ru)
debian.nsu.ru                   /debian/                        /debian/                        amd64 i386
debian.udsu.ru                  /debian/                        /debian/                        amd64 i386
ftp.psn.ru                      /debian/                        /debian/                        alpha amd64 hurd-i386 i386
ftp.corbina.net                 /debian/                                                        amd64 i386 ia64
debian.samara.ru                                                /debian/                        amd64 i386
ftp.mipt.ru                     /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.yandex.ru                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

SE Sweden
---------
ftp.se.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.acc.umu.se)
ftp.sunet.se                    /pub/Linux/distributions/debian//pub/Linux/distributions/debian/alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.port80.se                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.ds.karen.hj.se              /pub/os/linux/debian/           /pub/os/linux/debian/           alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.lth.se                   /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.df.lth.se                   /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.ru.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.chg.ru)
ftp.psn.ru                      /debian/                        /debian/                        alpha amd64 hurd-i386 i386
ftp.corbina.net                 /debian/                                                        amd64 i386 ia64
ftp.mipt.ru                     /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.yandex.ru                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.debian.chuvsu.ru            /debian/                        /debian/                        amd64 i386

SE Sweden
---------
ftp.se.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.acc.umu.se)
ftp.sunet.se                    /pub/Linux/distributions/debian//pub/Linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.port80.se                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.ds.karen.hj.se              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.bsnet.se                 /debian/                        /debian/                        amd64 i386
debian.lth.se                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.df.lth.se                   /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream

SG Singapore
------------
mirror.nus.edu.sg               /pub/Debian/                    /Debian/                        amd64 i386

SI Slovenia
-----------
<<<<<<< HEAD
ftp.si.debian.org               /debian/                        /debian/                        alpha amd64 i386 ia64 m68k powerpc sparc
  (ftp.camtp.uni-mb.si)
ftp.arnes.si                    /packages/debian/               /pub/packages/debian/           amd64 hurd-i386 i386
debian.prunk.si                 /debian/                        /debian/                        amd64 i386

SK Slovakia
-----------
ftp.sk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.tuke.sk)
mirror.ynet.sk                                                  /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.debian.sk                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.antik.sk                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

SV El Salvador
--------------
debian.ues.edu.sv               /debian/                        /debian/                        amd64 i386 ia64
=======
ftp.si.debian.org               /debian/                        /debian/                        amd64 i386 powerpc sparc
  (ftp.camtp.uni-mb.si)
ftp.arnes.si                    /packages/debian/               /pub/packages/debian/           amd64 hurd-i386 i386
debian.prunk.si                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

SK Slovakia
-----------
ftp.sk.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.debian.sk)
debian.ynet.sk                  /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.antik.sk                    /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

SV El Salvador
--------------
debian.ues.edu.sv                                               /debian/                        amd64 i386 ia64
>>>>>>> upstream

TH Thailand
-----------
ftp.coe.psu.ac.th               /debian/                        /debian/                        i386
<<<<<<< HEAD
ftp.thaios.net                                                  /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
debian.thaios.net                                               /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
ftp.debianclub.org              /debian/                        /debian/                        amd64 i386

TR Turkey
---------
<<<<<<< HEAD
ftp.tr.debian.org               /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.ankara.edu.tr)
ftp.linux.org.tr                /pub/debian/                                                    amd64 i386
godel.cs.bilgi.edu.tr           /debian/                        /debian/                        hurd-i386 i386
debian.eso-es.net                                               /debian/                        amd64 i386 ia64 sparc
debian.comu.edu.tr              /debian/                        /debian/                        amd64 i386 ia64 powerpc sparc

TW Taiwan
---------
ftp.tw.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (debian.linux.org.tw)
debian.csie.ntu.edu.tw          /pub/debian/                    /debian/                        amd64 hurd-i386 i386
ftp.twaren.net                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
opensource.nchc.org.tw          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.isu.edu.tw                  /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.nctu.edu.tw              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.nttu.edu.tw              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.csie.nctu.edu.tw         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.ncnu.edu.tw                 /Linux/Debian/debian/           /Linux/Debian/debian/           alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.cse.yzu.edu.tw              /pub/Linux/debian/debian/       /pub/Linux/debian/debian/       alpha amd64 arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc

UA Ukraine
----------
debian.osdn.org.ua              /pub/Debian/debian/             /debian/                        i386
debian.org.ua                   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.3logic.net                  /debian/                                                        amd64 i386
mirror.mirohost.net             /debian/                        /debian/                        amd64 i386

US United States
----------------
ftp.us.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
  (ftp.egr.msu.edu, mirrors.kernel.org, debian.osuosl.org, debian.lcs.mit.edu)
debian.crosslink.net            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.gtlib.gatech.edu            /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.egr.msu.edu                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
distro.ibiblio.org              /pub/linux/distributions/debian//debian/                        amd64 i386 ia64
ftp-mirror.internap.com         /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.cerias.purdue.edu           /pub/os/debian/                 /pub/os/debian/                 amd64 hurd-i386 i386 ia64 powerpc sparc
ftp.cs.unm.edu                  /mirrors/debian/                                                alpha arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.cs.wisc.edu              /pub/mirrors/linux/debian/      /pub/mirrors/linux/debian/      amd64 i386
ftp.uwsg.indiana.edu            /linux/debian/                  /linux/debian/                  alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
natasha.stmarytx.edu            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.ndlug.nd.edu                /debian/                        /mirrors/debian/                alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.uchicago.edu             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
carroll.aset.psu.edu            /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.fifi.org                 /pub/debian/                    /debian/                        amd64 i386
gladiator.real-time.com         /linux/debian/                                                  alpha amd64 i386 powerpc sparc
mirrors.kernel.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirrors.xmission.com            /debian/                        /debian/                        amd64 hurd-i386 i386 powerpc sparc
ftp.keystealth.org              /debian/                        /debian/                        amd64 hurd-i386 i386 ia64 mips sparc
ftp.lug.udel.edu                /pub/debian/                    /pub/debian/                    amd64 hurd-i386 i386 powerpc sparc
debian.lcs.mit.edu              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
linux.csua.berkeley.edu                                         /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.silug.org                   /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa i386 mips mipsel powerpc sparc
debian.secsup.org               /pub/linux/debian/              /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
techweb.rfa.org                 /debian/                        /debian/                        amd64 i386
debian.osuosl.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.anl.gov                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
sluglug.ucsc.edu                                                /debian/                        amd64 hurd-i386 i386 powerpc sparc
mirrors.geeks.org               /debian/                        /debian/                        amd64 i386
debian.midco.net                                                /debian/                        i386
mirrors.usc.edu                 /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mirrors.pair.com         /                               /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
lug.mtu.edu                     /debian/                        /debian/                        alpha amd64 hppa i386 mips mipsel powerpc sparc
debian.mirrors.tds.net          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.cites.uiuc.edu           /pub/debian/                    /pub/debian/                    amd64 hurd-i386 i386 ia64 powerpc sparc
mirrors.tummy.com               /pub/ftp.debian.org/            /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
debian.mirror.frontiernet.net   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
cudlug.cudenver.edu             /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.tucdemonic.org                                           /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
bigmirror.crossbowproject.net   /pub/debian/                                                    alpha arm armel hppa i386 ia64 m68k mips mipsel powerpc s390 sparc
=======
ftp.tr.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.ankara.edu.tr)
ftp.linux.org.tr                /debian/                        /debian/                        amd64 i386
godel.cs.bilgi.edu.tr           /debian/                        /debian/                        hurd-i386 i386
debian.eso-es.net                                               /debian/                        amd64 i386 ia64 sparc
debian.comu.edu.tr              /debian/                        /debian/                        amd64 i386 ia64 powerpc sparc
ftp.metu.edu.tr                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

TW Taiwan
---------
ftp.tw.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.linux.org.tw)
debian.csie.ntu.edu.tw          /pub/debian/                    /debian/                        amd64 hurd-i386 i386
ftp.twaren.net                  /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
opensource.nchc.org.tw          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.isu.edu.tw                  /debian/                        /debian/                        alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc
debian.nctu.edu.tw              /debian/                        /debian/                        ALL alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.nttu.edu.tw              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.csie.nctu.edu.tw         /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.cse.yzu.edu.tw              /pub/Linux/debian/debian/       /pub/Linux/debian/debian/       alpha amd64 arm armel hppa i386 ia64 mips mipsel powerpc s390 sparc

UA Ukraine
----------
ftp.ua.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (debian.org.ua)
debian.osdn.org.ua              /pub/Debian/debian/             /debian/                        i386
ftp.3logic.net                  /debian/                                                        amd64 i386
mirror.mirohost.net             /debian/                        /debian/                        amd64 i386
ftp2.debian.org.ua              /debian/                        /debian/                        amd64 i386

US United States
----------------
ftp.us.debian.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
  (ftp.egr.msu.edu, mirrors.kernel.org, debian.osuosl.org, debian.lcs.mit.edu)
ftp.gtlib.gatech.edu            /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.egr.msu.edu                 /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
distro.ibiblio.org              /pub/linux/distributions/debian//debian/                        amd64 i386 ia64
ftp-mirror.internap.com         /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.cs.wisc.edu              /pub/mirrors/linux/debian/      /pub/mirrors/linux/debian/      amd64 i386
ftp.uwsg.indiana.edu            /linux/debian/                  /linux/debian/                  alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
natasha.stmarytx.edu            /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.ndlug.nd.edu                /debian/                        /mirrors/debian/                alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.uchicago.edu             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
carroll.aset.psu.edu            /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
gladiator.real-time.com         /linux/debian/                                                  alpha amd64 i386 powerpc sparc
mirrors.kernel.org              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirrors.xmission.com            /debian/                        /debian/                        amd64 hurd-i386 i386 powerpc sparc
ftp.lug.udel.edu                /pub/debian/                    /pub/debian/                    amd64 hurd-i386 i386 powerpc sparc
debian.lcs.mit.edu              /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
linux.csua.berkeley.edu                                         /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.silug.org                   /pub/debian/                    /pub/debian/                    alpha amd64 arm armel hppa i386 mips mipsel powerpc sparc
debian.secsup.org               /pub/linux/debian/              /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.osuosl.org               /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.anl.gov                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
sluglug.ucsc.edu                                                /debian/                        amd64 hurd-i386 i386 powerpc sparc
mirrors.geeks.org               /debian/                        /debian/                        amd64 i386
mirrors.usc.edu                 /pub/linux/distributions/debian//pub/linux/distributions/debian/alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mirrors.pair.com         /                               /                               alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
lug.mtu.edu                     /debian/                        /debian/                        alpha amd64 hppa i386 mips mipsel powerpc sparc
debian.mirrors.tds.net          /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.cites.uiuc.edu           /pub/debian/                    /pub/debian/                    amd64 hurd-i386 i386 ia64 powerpc sparc
mirrors.tummy.com               /debian/                        /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.mirror.frontiernet.net   /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
cudlug.cudenver.edu                                             /debian/                        alpha amd64 arm hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream
mirror.cc.columbia.edu          /pub/linux/debian/debian/       /pub/linux/debian/debian/       amd64 i386 powerpc
ftp.grokthis.net                /mirrors/debian/                                                amd64 i386
mirrors.xenir.com                                               /debian/                        amd64 arm armel i386 powerpc
debian.mirrors.easynews.com                                     /linux/debian/                  amd64 i386
<<<<<<< HEAD
debian.ams.sunysb.edu                                           /debian/                        alpha amd64 arm armel hppa hurd-i386 ia64 m68k mips mipsel powerpc s390 sparc
mirrors.acm.jhu.edu                                             /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.uga.edu                     /debian/                        /debian/                        i386
opensourcemirrors.org           /debian/                        /debian/                        amd64 i386
mirror.steadfast.net                                            /debian/                        amd64 i386
mirror.espri.arizona.edu        /debian/                        /debian/                        alpha amd64 arm armel i386 mips mipsel powerpc sparc
ftp.utexas.edu                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
mirror.fdcservers.net           /debian/                        /debian/                        amd64 i386
mirror4.lockdownhosting.com     /debian/                        /debian/                        amd64 i386 ia64 powerpc
mirror.rit.edu                  /debian/                        /debian/                        alpha amd64 arm armel i386 powerpc sparc
debian.corenetworks.net                                         /debian/                        amd64 i386

VE Venezuela
------------
debian.unesr.edu.ve                                             /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.ula.ve                      /debian/                        /debian/                        alpha amd64 i386 ia64 powerpc sparc
=======
debian.ams.sunysb.edu                                           /debian/                        alpha amd64 arm armel hppa hurd-i386 ia64 mips mipsel powerpc s390 sparc
mirrors.acm.jhu.edu                                             /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.uga.edu                     /debian/                        /debian/                        i386
mirror.steadfast.net                                            /debian/                        amd64 i386
ftp.utexas.edu                  /pub/debian/                    /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.fdcservers.net           /debian/                        /debian/                        amd64 i386
mirror.rit.edu                  /debian/                        /debian/                        alpha amd64 arm armel i386 powerpc sparc
debian.corenetworks.net                                         /debian/                        amd64 i386
mirror.its.uidaho.edu           /debian/                        /pub/debian/                    alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
debian.cs.binghamton.edu        /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
mirror.hmc.edu                                                  /debian/                        amd64 hppa i386 powerpc

UZ Uzbekistan
-------------
debian.stream.uz                /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

VE Venezuela
------------
debian.unesr.edu.ve                                             /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
>>>>>>> upstream

ZA South Africa
---------------
ftp.sun.ac.za                   /debian/                        /ftp/debian/                    amd64 i386
<<<<<<< HEAD
debian.mirror.ac.za             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc
ftp.is.co.za                    /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 m68k mips mipsel powerpc s390 sparc

-------------------------------------------------------------------------------
Last modified: Tue Apr 29 19:52:14 2008             Number of sites listed: 409
=======
debian.mirror.ac.za             /debian/                        /debian/                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc
ftp.is.co.za                    /debian/                                                        alpha amd64 arm armel hppa hurd-i386 i386 ia64 mips mipsel powerpc s390 sparc

-------------------------------------------------------------------------------
Last modified: Sat Feb 21 01:52:19 2009             Number of sites listed: 416
>>>>>>> upstream
