# libhoney [![Build Status](https://travis-ci.org/honeycombio/libhoney-rb.svg?branch=master)](https://travis-ci.org/honeycombio/libhoney-rb) [![Gem Version](https://badge.fury.io/rb/libhoney.svg)](https://badge.fury.io/rb/libhoney)

![Honeycomb logo](https://docs.honeycomb.io/images/hcio_logo.svg)

Ruby gem for sending events to [Honeycomb](https://www.honeycomb.io), a service for debugging your software in production.

- [Usage and Examples](https://docs.honeycomb.io/sdk/ruby/)
- [API Reference](https://www.rubydoc.info/gems/libhoney)

## Contributions

Features, bug fixes and other changes to `libhoney` are gladly accepted. Please
open issues or a pull request with your change. Remember to add your name to the
CONTRIBUTORS file!

All contributions will be released under the Apache License 2.0.

### Releasing a new version

Travis will automatically upload tagged releases to Rubygems. To release a new
version, run
```
bump patch --tag   # Or bump minor --tag, etc.
git push --follow-tags
```
