# Simple Bayes Changelog

## v0.12.2 [2017-07-30]

- Updated dependencies

## v0.12.1 [2017-07-18]

- Multiple instances of stop-words are now correctly ignored - thanks [@claytongentry](https://github.com/claytongentry)!

## v0.11.0 [2016-08-15]

- The `:stem` option now accepts any stemming function (still defaults to `false`) - thanks [@duijf](https://github.com/duijf)!

## v0.10.0 [2016-08-09]

- Implemented `:dets` storage option
- Fixed Bernoulli model's float overflow when dealing with large amount of data

## v0.9.0 [2016-08-04]

- Added `top` option for restricting number of results
- Added `encoded_data` option for use with custom storages

## v0.8.0 [2016-07-26]

- Introduced the storage mechanism (defaults to `:memory`)
- Implemented file system storage

## v0.7.1 [2016-07-23]

- Adjusted the `:smoothing` option

## v0.7.0 [2016-07-23]

- Implemented Bernoulli model

## v0.6.0 [2016-07-21]

- Implemented Binarized Multinomial model

## v0.5.2 [2016-07-20]

- Upgraded the `stemmer` dependency

## v0.5.1 [2016-07-19]

- Upgraded the `stemmer` dependency

## v0.5.0 [2016-07-19]

- Integrated `stemmer`, introduced word stemming

## v0.4.4 [2016-07-17]

- Performance improvements
- Enforce lowercase matching

## v0.4.3 [2016-07-16]

- Performance improvements

## v0.4.2 [2016-07-16]

- Documentation fix

## v0.4.1 [2016-07-16]

- Improved documentation

## v0.4.0 [2016-07-16]

- Refactored for better readability and tests

## v0.3.1 [2016-07-16]

- Tweaked configurations
- Tweaked the test suite

## v0.3.0 [2016-07-16]

- Implemented TF-IDF
- Fixed frequency/weight accumulator
- More precise keyword matching

## v0.2.0 [2016-07-15]

- Implemented stop words
- `classify` now returns ordered results
- User-configurable options

## v0.1.0 [2016-07-15]

- Multinomial naive bayes implementation
- Optional keyword weighting
