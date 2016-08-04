# libphonenumber [![Build Status](https://travis-ci.org/mattbornski/libphonenumber.png)](http://travis-ci.org/mattbornski/libphonenumber) [![Build status](https://ci-beta.appveyor.com/api/projects/status/rmhkeri71ystuk7w)](https://ci-beta.appveyor.com/project/mattbornski/libphonenumber)

NodeJS port of Google's libphonenumber (thanks to SocialCam), packaged for npm

## Installation

### Installing npm (node package manager)
```
curl http://npmjs.org/install.sh | sh
```

### Installing libphonenumber
```
npm install libphonenumber
```

## Example Usage

```javascript
var libphonenumber = require('libphonenumber')

libphonenumber.intl("0912102034", "vn");
// +84 91 210 20 34

libphonenumber.e164("0912102034", "vn");
// +84912102034

```


