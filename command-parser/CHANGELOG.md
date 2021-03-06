# Changelog

Changelog for `twilight-command-parser`.

## [0.2.3] - 2020-12-30

### Enhancements

Export the `config` module's iterators to allow them to be documented by rustdoc
([#646] - [@vivian]).

[#646]: https://github.com/twilight-rs/twilight/pull/646

## [0.2.2] - 2020-11-02

Remove the `unicode-segmentation` dependency due to the functionality used from
it also being in the stdlib ([#585] - [@vivian]).

## [0.2.1] - 2020-10-31

### Fixes

Take whitespace after prefixes into account when creating the initial index for
argument iterating, for example when the prefix is a user mention. This fixes
the first argument being the last letter of the command
name ([#584] - [@vivian]).

## [0.2.0] - 2020-10-30

This major version bump of the Command Parser is primarily done to match all of
the other crates in the ecosystem receiving a major version bump. There are no
significant API changes.

### Fixes

Add unicode support to the `Arguments` iterator ([#575] - [@AsianIntel]).

## [0.2.0-beta.0] - 2020-10-10

This major version bump of the Command Parser is done to match all of the other
crates in the ecosystem receiving a major version bump. There are no changes.

## [0.1.2] - 2020-10-07

### Fixes

- Fix typos in links ([#515] - [@nickelc])

## [0.1.1] - 2020-09-17

### Fixes

- Fix benchmark compilation ([#511] - [@Erk-])

## [0.1.0] - 2020-09-13

Initial release.

[@AsianIntel]: https://github.com/AsianIntel
[@Erk-]: https://github.com/Erk-
[@nickelc]: https://github.com/nickelc
[@vivian]: https://github.com/vivian

[#585]: https://github.com/twilight-rs/twilight/pull/585
[#584]: https://github.com/twilight-rs/twilight/pull/584
[#575]: https://github.com/twilight-rs/twilight/pull/575
[#515]: https://github.com/twilight-rs/twilight/pull/515
[#511]: https://github.com/twilight-rs/twilight/pull/511

[0.2.2]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.2.2
[0.2.1]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.2.1
[0.2.0]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.2.0
[0.2.0-beta.0]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.2.0-beta.0
[0.1.2]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.1.2
[0.1.1]: https://github.com/twilight-rs/twilight/releases/tag/command-parser-v0.1.1
[0.1.0]: https://github.com/twilight-rs/twilight/releases/tag/v0.1.0
