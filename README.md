BearSSL
==========

BearSSL is an implementation of the SSL/TLS protocol (RFC 5246) written in C.

Features
--------

It aims at offering the following features:
 * Be correct and secure. In particular, insecure protocol versions and choices of algorithms are not supported, by design; cryptographic algorithm implementations are constant-time by default.
 * Be small, both in RAM and code footprint. For instance, a minimal server implementation may fit in about 20 kilobytes of compiled code and 25 kilobytes of RAM.
 * Be highly portable. BearSSL targets not only “big” operating systems like Linux and Windows, but also small embedded systems and even special contexts like bootstrap code.
 * Be feature-rich and extensible. SSL/TLS has many defined cipher suites and extensions; BearSSL should implement most of them, and allow extra algorithm implementations to be added afterwards, possibly from third parties.
 * MIT license.

Status
------

Current version 0.2. It is considered alpha-quality software, which means that it runs but it probably has bugs,
some of which being certainly exploitable vulnerabilities. A lot more testing and documentation is needed before
BearSSL can be deemed usable in production.

For more details, see BearSSL library in lib/ directory.


Authors
------

BearSSL library copyright (c) 2016 Thomas Pornin.

BearSSL PlatformIO wrapper copyrigh (c) 2016 by Lubos Medovarsky.
