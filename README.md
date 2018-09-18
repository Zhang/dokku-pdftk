# dokku-pdftk

dokku-pdftk is an awesome plugin for [dokku][dokku] that properly installs the pdftk into the docker instance.

## Installation

On your dokku server:
```sh
# On 0.3.x
git clone https://github.com/Zhang/dokku-pdftk /var/lib/dokku/plugins/dokku-pdftk

# On 0.4.x
dokku plugin:install https://github.com/Zhang/dokku-pdftk.git pdftk
```

All future deployments will have dokku-pdftk installed.
