Adelphia Core
=============

Setup
---------------------
Adelphia Core is the original Adelphia client and it builds the backbone of the network. It downloads and, by default, stores the entire history of Adelphia transactions (which is currently more than 7 GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download Adelphia Core, visit [adelphia.org](https://adelphia.org).

Running
---------------------
The following are some helpful notes on how to run Adelphia on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/adelphia-qt` (GUI) or
- `bin/adelphiad` (headless)

### Windows

Unpack the files into a directory, and then run adelphia-qt.exe.

### OS X

Drag Adelphia-Core to your applications folder, and then run Adelphia-Core.

### Need Help?

* See the documentation at the [Adelphia Wiki](https://adelphia.info/)
for help and more information.
* Ask for help on [#adelphia](http://webchat.freenode.net?channels=adelphia) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=adelphia).
* Ask for help on the [AdelphiaTalk](https://adelphiatalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Adelphia on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Adelphia repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/adelphia/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [AdelphiaTalk](https://adelphiatalk.io/) forums.
* Discuss general Adelphia development on #adelphia-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=adelphia-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
