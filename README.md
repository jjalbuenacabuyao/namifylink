# namifylink

[![Build](https://github.com/arshadkazmi42/namifylink/actions/workflows/nodejs.yml/badge.svg)](https://github.com/arshadkazmi42/namifylink/actions/workflows/nodejs.yml)

Get domain name from url

## Install

```
npm i namifylink
```

## Usage

```javascript

const namifyLink = require('namifylink');

const fileName = namifyLink('https://github.com/arshadkazmi42');
console.log(fileName);

// Output
// github-com


const fileName = namifyLink('https://mail.google.com/arshadkazmi42');
console.log(fileName);

// Output
// mail-google-com

```

## Contributing

Interested in contributing to this project?
You can log any issues or suggestion related to this library [here](https://github.com/arshadkazmi42/namifylink/issues/new)

Read our contributing [guide](CONTRIBUTING.md) on getting started with contributing to the codebase

