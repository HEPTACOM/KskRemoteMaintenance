# Remote Maintenance
#### Shopware plugin to access filesystem via WebDAV protocol

![Packagist Version](https://img.shields.io/packagist/v/heptacom/shopware-ksk-remote-maintenance?style=flat-square)
![PHP from Packagist](https://img.shields.io/packagist/php-v/heptacom/shopware-ksk-remote-maintenance?style=flat-square)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](./LICENSE.md)

![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/heptacom/KskRemoteMaintenance?style=flat-square)
[![GitHub issues](https://img.shields.io/github/issues/HEPTACOM/KskRemoteMaintenance?style=flat-square)](https://github.com/HEPTACOM/KskRemoteMaintenance/issues)
[![GitHub forks](https://img.shields.io/github/forks/HEPTACOM/KskRemoteMaintenance?style=flat-square)](https://github.com/HEPTACOM/KskRemoteMaintenance/network)
[![GitHub stars](https://img.shields.io/github/stars/HEPTACOM/KskRemoteMaintenance?style=flat-square)](https://github.com/HEPTACOM/KskRemoteMaintenance/stargazers)
![GitHub watchers](https://img.shields.io/github/watchers/heptacom/KskRemoteMaintenance?style=flat-square)
![Packagist](https://img.shields.io/packagist/dt/heptacom/shopware-ksk-remote-maintenance?style=flat-square)

![GitHub contributors](https://img.shields.io/github/contributors/heptacom/KskRemoteMaintenance?style=flat-square)
![GitHub commit activity](https://img.shields.io/github/commit-activity/y/heptacom/KskRemoteMaintenance?style=flat-square)

This project is aimed towards developers that need access to the file system of a shopware system but do not have ftp
or similar access. It enables the shopware installation to act as a WebDAV server and be accessed with a backend user
and a corresponding api key. All that is needed to access the file system is a backend user that is permitted to use the
api and the WebDAV interface.

Api permission can be granted in the user settings (where you can also find the api key) and WebDAV permission can be
granted in the acl settings where you have to add the privilege to a role of backend users.

After this initial setup you can use your WebDAV client of choice to access the file system under this URL:
`http(s)://<your-shop-domain.tld>/webdav/index/index/`  

## Changes

View the [CHANGELOG](CHANGELOG.md) file attached to this project.

## License

See [LICENSE.md](./LICENSE.md)

