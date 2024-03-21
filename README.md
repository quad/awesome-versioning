# Awesome Versioning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Software versioning is the process of assigning either unique version names or unique version numbers to unique states of computer software.
> ([Wikipedia](https://en.wikipedia.org/wiki/Software_versioning))

Welcome to our curated list of all things awesome related to the practice of versioning software!

## Contents

- [Tools](#tools)
- [Versioning Schemes](#versioning-schemes)
    - [General Schemes](#general-schemes)
    - [Restricted Schemes](#restricted-schemes)

---

## Tools

_Helpful programs to ease the hard task of assigning versions._

- [Semantic Version Util (svu)](https://github.com/caarlos0/svu) <!-- 2017-12-14, 89bb82f --> - Print the current version, increase patch/minor/major manually or just get the next tag based on your git log.

- [BumpVer](https://github.com/mbarkhau/bumpver) <!-- 2018-11-12, 431596f --> - Search for and update version strings in your project files.

## Versioning Schemes

_Unique ways to uniquely version the unique states of unique projects!_

### General Schemes

_The author(s) or maintainer(s) of the following schemes **MAY** intend them for use by projects of all maturity levels._

- [Semantic Versioning (SemVer)](https://semver.org/) <!-- 2011-06-08, v1.1.0-beta --> - Version numbers and the way they change convey meaning about the underlying code and what has been modified from one version to the next.

- [Break Versioning (BreakVer)](https://www.taoensso.com/break-versioning) <!-- 2014-08-15, 5c74948 --> - Emphasizes the maximum amount of damage a version update could inflict.

- [Calendar Versioning (CalVer)](https://calver.org/) <!-- 2016-03-25, 52ae856 --> - A versioning convention based on your project's release calendar, instead of arbitrary numbers.

- [0-based Versioning (ZeroVer)](https://0ver.org/) <!-- 2018-03-03, f268d52 --> - Your software's major version should never exceed the first and most important number in computing- zero.

- [Romantic Versioning (RomVer)](https://github.com/romversioning/romver) <!-- 2019-04-18, 45e1751 --> - An attempt to extract 'versioning spec' from real-world usage of software versions (like in Node, Rails, PHP, jQuery, NPM, Linux Kernel).

- [Chronologic Versioning (ChronVer)](https://chronver.org/) - <!-- 2019-05-05, ec169a6-->  Communicate changes to your project with specific temporal-based increments to the version number.

- [Hash Versioning (HashVer)](https://miniscruff.github.io/hashver/) <!-- 2020-01-12, 2e462c3 --> and [GitDate](https://taylorbrazelton.com/2022/06/06/2022-06-06-bye-bye-semantic-versioning-say-hello-to-gitdate/) <!-- 2022-06-06 --> - Suited for constant small releases

- [StableVer](https://gist.github.com/brandonbloom/465625acaf0120354614e7fc0c117c62) <!-- 2021-02-22, d2e08a3 --> - It should always be possible to migrate from major version N to major version N+1 without breaking changes -- provided that you are not using any features that were marked deprecated in version N.

- [Pragmatic Versioning](https://pragmaticversioning.com/) <!-- 2023-12-04, 70b76ff --> - Communicates changes to a package to package consumers, while retaining simple semantics for package maintainers.

- [Intended Effort Versioning (EffVer)](https://jacobtomlinson.dev/effver/) <!-- 2024-01-15, f12f0e8 --> - Version your code by the effort required to upgrade.

- [SoloVer](https://beza1e1.tuxen.de/SoloVer) <!-- 2024-03-16 --> - Intentionally do not try to communicate "backward compatibility" as there is no objective and satisfying definition anyways.

### Restricted Schemes

_Programmers are warned that the author(s) or maintainer(s) of the following schemes **MAY NOT** intend them for general use._

<!-- lint disable awesome-list-item -->
- [πVer and eVer](https://tug.org/TUGboat/Articles/tb11-4/tb30knut.pdf) <!-- 1990-10-03 -->
  > The current version number for is 3.1, and for METAFONT it is 2.7.
  > If corrections are necessary, the next versions of TeX will be 3.14, then 3.141, then 3.1415, …, converging to the ratio of a circle's circumference to its diameter;
  > for METAFONT the sequence will be 2.71, 2.718, …, converging to the base of natural logarithms.
  > I intend to be fully responsible for all changes to these systems for the rest of my life.
  > I will periodically study reports of apparent bugs, and I will decide whether changes need to be made.
  > Rewards will be paid to the first finders of any true bugs, at my discretion, but I can no longer afford to double the size of the reward each year.
  > Whenever I have created a new version, I will put it in the official master TeX archive, which currently resides at Stanford University.
  > At the time of my death, it is my intention that the then-current versions of TeX and METAFONT be forever left unchanged, except that the final version numbers to be reported in the "banner" lines of the programs should become `TeX, Version $\pi$` and `METAFONT, Version $e$` respectively.
  > From that moment on, all "bugs" will be permanent "features."
<!-- lint enable awesome-list-item -->

- [Haskell Package Versioning Policy (PVP)](https://pvp.haskell.org/) <!-- 2014-04-09, ecc928d --> - An attempt to formalize the informal policy in use in the Haskell community.

- [WendtVer](https://wendtver.org/) <!-- 2017-09 --> - Version numbers and the way they change convey utter chaos and no meaning about the underlying code, but are easy to figure out what the next version will be.
