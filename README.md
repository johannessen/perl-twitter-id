Twitter::ID
===========

This Perl module allows reading the date from a "Snowflake" Twitter ID.

Twitter IDs from before the introduction of Snowflake in late 2010 are
currently unsupported.

Since Twitter has decided to disallow anonymous access on 30 June 2023,
I have no further use for this module and development has ceased.
If you'd like to take over, I'd be happy to accept your request for
transfer of [PAUSE](https://pause.perl.org/) primary permission.


Installation
------------

Released versions of [Twitter::ID][] may be installed via CPAN:

    cpanm Twitter::ID

[![CPAN distribution](https://badge.fury.io/pl/Twitter-ID.svg)](https://badge.fury.io/pl/Twitter-ID)

To create a tarball of a development version from this
repository and install it, run the following steps.

1. `git clone https://github.com/johannessen/perl-twitter-id && cd perl-twitter-id`
1. `cpanm Dist::Zilla::PluginBundle::Author::AJNN`
1. `dzil build`
1. `cpanm <archive>.tar.gz`

This is a “Pure Perl” module, so you generally do not need
Dist::Zilla to contribute patches.
You can simply clone the repository and run the test suite
using `prove` instead.

[Twitter::ID]: https://metacpan.org/release/Twitter-ID
