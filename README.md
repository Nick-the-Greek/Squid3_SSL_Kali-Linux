
                       Squid3 v.3.3.8 - SSL enabled - Kali Linux - Sat 25 Oct 2014

Based on:  hkerem's squid3-ssl
------------------------------

Files:
====
1. squid3_3.3.8-1.1Kali1_amd64
   * squid3_3.3.8-1.1Kali1.dsc
   * squid3_3.3.8-1.1Kali1.tar.gz
   * squid3_3.3.8-1.1Kali1_amd64.changes
   * squid3_3.3.8-1.1Kali1_amd64.deb
   * squid3-common_3.3.8-1.1Kali1_all.deb
   * squid3-dbg_3.3.8-1.1Kali1_amd64.deb
   * squid-cgi_3.3.8-1.1Kali1_amd64.deb
   * squidclient_3.3.8-1.1Kali1_amd64.deb
   * squid-langpack_20140506.orig.tar.gz
   * squid-langpack_20140506-1.1Kali1.diff.gz
   * squid-langpack_20140506-1.1Kali1.dsc
   * squid-langpack_20140506-1.1Kali1_all.changes
   * squid-langpack_20140506-1.1Kali1_all.deb

2. squid3_3.3.8-1.1Kali1_i386
   * squid3_3.3.8-1.1Kali1.dsc
   * squid3_3.3.8-1.1Kali1.tar.gz
   * squid3_3.3.8-1.1Kali1_i386.changes
   * squid3_3.3.8-1.1Kali1_i386.deb
   * squid3-common_3.3.8-1.1Kali1_all.deb
   * squid3-dbg_3.3.8-1.1Kali1_i386.deb
   * squid-cgi_3.3.8-1.1Kali1_i386.deb
   * squidclient_3.3.8-1.1Kali1_i386.deb
   * squid-langpack_20140506.orig.tar.gz
   * squid-langpack_20140506-1.1Kali1.diff.gz
   * squid-langpack_20140506-1.1Kali1.dsc
   * squid-langpack_20140506-1.1Kali1_amd64.changes
   * squid-langpack_20140506-1.1Kali1_all.deb

Installation
============
Squid3 v.3.3.8 SSL is incompatible with any previous version of Squid3. So, if you have installed any version of Squid3 e.g. Kali offers Squid3 v.3.1.20 you must uninstall it first :

apt-get --purge remove -y squid3 squid3-common squid-langpack

For amd64 architecture (minimal installation) :

cd squid3_3.3.8-1.1Kali1_amd64
dpkg -i squid3_3.3.8-1.1Kali1_amd64.deb squid3-common_3.3.8-1.1Kali1_all.deb squid-langpack_20140506-1.1Kali1_all.deb

For i386 architecture (minimal installation) :

cd squid3_3.3.8-1.1Kali1_i386
dpkg -i squid3_3.3.8-1.1Kali1_i386.deb squid3-common_3.3.8-1.1Kali1_all.deb squid-langpack_20140506-1.1Kali1_all.deb
  
Tested
======

  - : Kali Linux
    - 1.0.6 (x32 / x64).
    - 1.0.7 (x32 / x64).
    - 1.0.8 (x32 / x64).
    - 1.0.9 (x32 / x64).

The Latest Version
==================

  Details of the latest version can be found on the Kali forums and here at github :
  <a href="  https://forums.kali.org/showthread.php?23036-SSL-Interception-with-Squid3-%28MITM%29">SSL Interception with Squid3/</a>



Documentation
=============

  No documentation available yet. Only this README file.

Licensing
=========

  Please see the file called COPYING.

References
=========
* <a href="https://github.com/hkerem/squid3-ssl">hkerem's squid3-ssl/</a>
* <a href="http://wiki.squid-cache.org/Features/DynamicSslCert">Dynamic SSL Certificate Generation/</a>
* <a href="http://wiki.squid-cache.org/Features/SslBump">Squid-in-the-middle SSL Bump/</a>
* <a href="http://wiki.squid-cache.org/Features/BumpSslServerFirst">SslBump using Bump-Server-First method/</a>
* <a href="http://wiki.squid-cache.org/Features/MimicSslServerCert">Mimic original SSL server certificate when bumping traffic/</a>

Contacts
========

You can contact me at:

<a href="https://forums.kali.org/member.php?24689-Nick_the_Greek">Nick_the_Greek Kali Forums/</a>
