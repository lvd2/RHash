# RHash

RHash  (Recursive  Hasher)   is  a  console  utility  for   calculation  and
verification of magnet links and various message digests, including CRC32, CRC32C,
MD4, MD5, SHA1, SHA256, SHA512, SHA3, AICH, ED2K, DC++ TTH, BitTorrent BTIH,
Tiger, GOST R 34.11-94, GOST R 34.11-2012, RIPEMD-160, HAS-160, EDON-R,  and
Whirlpool.

Message digests are used to ensure and verify integrity  of large volumes of
data for a long-term storing or transferring.

### Program features:
 * Ability to process directories recursively.
 * Output in a predefined (SFV, BSD-like) or a user-defined format.
 * Calculation of Magnet links.
 * Updating hash files (adding message digests of files missing in the hash file).
 * Calculates several message digests in one pass.
 * Portability: the program works the same on Linux, Unix, macOS or Windows.

## Installation
```shell
./configure && make install
```
For more complicated cases of installation see the [INSTALL.md] file.

## Documentation

* RHash [ChangeLog]
* [The LibRHash Library] documentation

## Links
* Project Home Page: http://rhash.sourceforge.net/
* Official Releases: https://github.com/rhash/RHash/releases/
* Binary Windows Releases: https://sf.net/projects/rhash/files/rhash/
* The table of the supported by RHash [hash functions](http://sf.net/p/rhash/wiki/HashFunctions/)
* ECRYPT [The Hash Function Zoo](http://ehash.iaik.tugraz.at/wiki/The_Hash_Function_Zoo)
* ECRYPT [Benchmarking of hash functions](https://bench.cr.yp.to/results-hash.html)

## Contribution
Please read the [Contribution guidelines](docs/CONTRIBUTING.md) document.

## License
The code is distributed under [BSD Zero Clause License](COPYING).

[INSTALL.md]: INSTALL.md
[The LibRHash Library]: docs/LIBRHASH.md
[ChangeLog]: ChangeLog
