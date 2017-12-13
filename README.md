 Return Of Bleichenbacher's Oracle Threat (ROBOT)
-----
ROBOT ATTACK TESTING TOOL
------
## Abstract:
Many web hosts are still vulnerable to one of the oldest attacks against RSA in TLS. We show that Bleichenbacher’s RSA vulnerability from 1998 is still very prevalent in the Internet and affects almost a third of the top 100 domains in the Alexa Top 1 Million list, among them Facebook and Paypal. We identified vulnerable products from at least eight different vendors and open source projects, among them F5, Citrix, Radware, Cisco, Erlang, Bouncy Castle, and WolfSSL. Further we have demonstrated practical exploitation by signing a message with the private key of facebook.com’s HTTPS certificate. Finally, we discuss countermeasures against Bleichenbacher attacks in TLS and recommend to deprecate the RSA encryption key exchange in TLS and the PKCS #1 v1.5 standard.
More Info:
* https://robotattack.org/
* https://eprint.iacr.org/2017/1189.pdf

Dependencies
============

This script needs Python3 and the gmpy2 library.

License
=======

This work is licensed as CC0 (public domain).

Authors
=======

Hanno Böck, Juraj Somorovsky, Craig Young
