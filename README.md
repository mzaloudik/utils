# Utilities
[![Build Status](https://travis-ci.org/ponury-kostek/utils.svg)](https://travis-ci.org/ponury-kostek/utils)
[![Coverage Status](https://coveralls.io/repos/ponury-kostek/utils/badge.svg?branch=master&service=github)](https://coveralls.io/github/ponury-kostek/utils?branch=master)
[![npm version](https://badge.fury.io/js/%40ponury%2Futils.svg)](https://badge.fury.io/js/%40ponury%2Futils)
[![npm](https://img.shields.io/npm/dt/@ponury/utils.svg)](https://www.npmjs.com/package/@ponury/utils)
### getType(value)
Returns type of given value or name of function/object.
### microtime()
Returns number of seconds since 1 January 1970 00:00:00 UTC.
### ucFirst(string)
Returns a string with the first character of ```string``` capitalized, if that character is alphabetic.
### lcFirst(string)
Returns a string with the first character of ```string``` lowercased, if that character is alphabetic.
### camelCase(string)
Returns a camel-cased string. Word boundaries are "-", "_", " "
### fileExists(path)
Checks whether a file or directory exists
```path``` must be absolute path
### extend(destination, source)
Copy properties from source to destination object
