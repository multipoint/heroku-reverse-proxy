# Reverse Proxy on Heroku

Run a reverse proxy using nginx on Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Installation

Use the [Deploy to Heroku](https://heroku.com/deploy) button above to create a
copy of the app, then configure the UPSTREAM_SERVER config variable.

## Development

```bash
heroku buildpacks:add --app APP_NAME heroku-community/nginx
```

## Credits

Updated to heroku-16 stack and recent community build pack for nginx.

Based on [octoberswimmer/heroku-reverse-proxy](https://github.com/octoberswimmer/heroku-reverse-proxy),
originally forked from [api-proxy-3scale-heroku](https://github.com/Taytay/api-proxy-3scale-heroku).
