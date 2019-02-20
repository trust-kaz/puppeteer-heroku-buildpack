# puppeteer-heroku-buildpack

**This fork of the [jontewks buildpack](https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack)
adds support for Chinese, Korean, and Japanese characters. Since it adds
22MBs for the font files, I've kept it as a separate build pack.**

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args: ['--no-sandbox'] }` in your call to `puppeteer.launch`

## Usage

To use the latest stable version from source code in this repository:

```sh-session
$ heroku buildpacks:set https://github.com/CoffeeAndCode/puppeteer-heroku-buildpack.git
```

## Issues

If you run into any issues with this buildpack, please open an issue on this repo and/or submit a PR that resolves it. Different versions of chrome have different dependencies and so some issues can creep in without me knowing. Thanks!
