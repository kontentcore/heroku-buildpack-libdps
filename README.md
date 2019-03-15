# Heroku Buildpack with libDPS

The buildpack installs private SSH key and then clones private repository
with libDPS binaries.

Set Base64 encoded SSH key to Heroku environment by:

```
heroku config:set SSH_KEY=$(cat path/to/private/key/id_rsa | base64)
```
