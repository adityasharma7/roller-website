title=Downloads
status=published
type=page
~~~~~~

## Apache Roller Releases

Releases of the Apache Roller blog server are made available to the general public at no charge, under the <a href="http://apache.org/licenses/">Apache License,</a> in both binary and source distributions.

### General Availability (GA) Releases</strong> - <em>Ready for Prime Time!</em>
__<a href="http://www.apache.org/dyn/closer.cgi/roller/roller-5.2/v5.2.0/">Roller 5.2.0</a> (&quot;best available&quot;)__

Previous source and binary distributions, including documentation, are available in the <a class="external" href="http://archive.apache.org/dist/roller/">Apache archives</a>.

Project releases are approved by vote of the Apache Roller Project Management Committee (PMC). Support for a release is provided by project volunteers on the project <a href="https://cwiki.apache.org/confluence/display/ROLLER/How+to+ask+for+help">mailing lists</a>. Bugs found in a release may be discussed on the list and reported through the <a href="https://issues.apache.org/jira/browse/ROL">issue tracker</a>. The user mailing list and issue tracker are the <strong>only</strong> support options hosted by the Apache Roller project.


Note: When downloading from a mirror, please be sure to verify that checksums and signatures are correct. To do so, use the checksum and signature files from the main Apache site at <a class="external" href="http://www.apache.org/dyn/closer.cgi/roller/roller-5.2/v5.2.0/bin/">http://www.apache.org/dyn/closer.cgi/roller/roller-5.2/v5.2.0/bin/</a>
Find here the KEYS file, which contains all OpenPGP keys we use to sign releases:
<a class="external" href="http://www.apache.org/dist/roller/">http://www.apache.org/dist/roller/</a>

The PGP signatures can be verified using PGP or GPG. First download the <a href="http://www.apache.org/dist/roller/KEYS">KEYS</a> as well as the ``asc`` signature file for the particular distribution. Make sure you get these files from the <a href="http://www.apache.org/dist/roller/">main distribution directory,</a> rather than from a mirror. Then verify the signatures using ``pgpk`` as follows:

    % pgpk -a KEYS
    % pgpv ${filename}.tar.gz.asc

or

    % pgp -ka KEYS
    % pgp ${filename}.tar.gz.asc
     
or

    % gpg --import KEYS
    % gpg --verify ${filename}.tar.gz.asc

Alternatively, you can verify the MD5 signature on the files. A Unix program called
``md5`` or ``md5sum`` is included in many Unix distributions. It is also available as part of <a href="http://www.gnu.org/software/textutils/textutils.html">GNU Textutils.</a> Windows users can get binary md5 programs from <a href="http://www.fourmilab.ch/md5/">here,</a> <a href="http://www.pc-tools.net/win32/freeware/console/">here,</a> or <a href="http://www.slavasoft.com/fsum/">here</a>.

If you want to build directly from the sources, please check the <a href="https://cwiki.apache.org/confluence/display/ROLLER/How+to+build+Roller">Project Wiki</a>.

