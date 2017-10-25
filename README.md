# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args:
['--no-sandbox'] }` in your call to `puppeteer.launch`

__This fork of the [jontewks buildpack](https://elements.heroku.com/buildpacks/jontewks/puppeteer-heroku-buildpack)
adds support for Chinese, Korean, and Japanese characters. Since it adds
22MBs for the font files, I've kept it as a separate build pack.__
