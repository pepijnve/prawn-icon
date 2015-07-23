# 0.7.0 - July 23, 2015

- Update Travis config to relax the versions of `Prawn` and `Ruby` that are tested against. See `.travis.yml` to see what versions are supported (though you shouldn't have issues with other versions).
- Implement inline_format for table icons. [#14](https://github.com/jessedoyle/prawn-icon/pull/14).
- Updated Octicons to v2.4.1. See [changelog](https://github.com/github/octicons/releases/) between versions 2.1.2 and 2.4.1.

# 0.6.4 - May 4, 2015

- [PaymentFont](http://paymentfont.io) is now supported and included in `Prawn::Icon`.

# 0.6.3 - March 4, 2015

- Relaxed Prawn runtime dependency from >= 1.3.0 to >= 1.1.0.
- Added CI tests for multiple versions of Prawn.
- Added missing `end` statement to example code in README.

# 0.6.2 - February 10, 2015

- Added this CHANGELOG.
- Added the `table_icon` method to simplify icon use in conjuction with `Prawn::Table`.
- Added a `.yardopts` file for better documentation.
- Clean `.gemspec` to increase readability.

# 0.6.1 - January 27, 2015

- Upgraded FontAwesome to `v4.3.0`.

# 0.6.0 - January 20, 2015

- Single-quoted attributes are now supported when using `inline_format: true`.
- Prawn is now specified as a runtime dependency of `prawn/icon`.

# 0.5.1 - November 2, 2014

- Bugfix for improperly cached font data.
- Added Codeclimate and Travis CI.

# 0.5.0 - October 29, 2014

- Initial public release.