# gas-kinlog

[![Build Status](https://travis-ci.org/announce/gas-kinlog.svg?branch=master)](https://travis-ci.org/announce/gas-kinlog)

## Prerequisite

* Docker
  * Verified with: Version 18.06.0-ce-mac70
* Node v8.x.x
* Yarn v1.x.x

## Development

Run the command below:

```bash
export PA_ACCESS_KEY="" PA_SECRET_KEY="" PA_ASSOCIATE_TAG=""
yarn start
```

For the release:

```bash
yarn run build
```

Then you will get the js file in `./dist`.

## Project Links

* Upstream work: [trunk](https://github.com/announce/gas-kinlog/compare/master...ymkjp:master)
* Dashboard: [Apps Script](https://script.google.com/home)
  * Trigger every 10 minutes

## Documents

* [Quotas for Google Services](https://developers.google.com/apps-script/guides/services/quotas)
  * Execution timeout is 6 minutes
