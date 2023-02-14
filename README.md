<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Paheko for YunoHost

[![Integration level](https://dash.yunohost.org/integration/paheko.svg)](https://dash.yunohost.org/appci/app/paheko) ![Working status](https://ci-apps.yunohost.org/ci/badges/paheko.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/paheko.maintain.svg)
[![Install Paheko with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=paheko)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Paheko quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

## Paheko

Paheko (we chose the name Paheko, a word from the Māori language meaning "to cooperate", illustrating the purpose of the software: to improve together the daily management of an association) is software for associative management. 

It is the tool of choice for managing an association, a sports club, an NGO, etc. It is designed to meet the needs of a small to medium-sized structure: management of members, accounting, website, note-taking in meetings, archiving and sharing of the association's operating documents, discussion between members, etc. etc. . 

## Garradin becomes Paheko! 
### Why change your name?

It appeared that the pronunciation of "Garradin" in French is sometimes a bit complicated, as is its spelling. 

There is already a commercial software called "Garradin" in Australia, which does finance for large groups. For the moment this was not a problem because our association management solution was only available in French and until then did not have much scope. But we would like to be able to offer the software in other languages in the years to come, and as Garradin (the French project) is starting to be quite well known, it seems necessary to limit the risk of confusion in the future with this commercial solution. 

You can now upgrade Garradin with Paheko !

![Logo Paheko](https://master.garradin.eu/garradin-devient-paheko/logo_v3_small-fs8.png)


**Shipped version:** 1.2.6~ynh1

**Demo:** https://paheko.cloud/essai/

## Screenshots

![Screenshot of Paheko](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### Migrate from Garradin

This package handle the migration from Garradin to Paheko. For that, you will have to upgrade your Garradin application with this repository. This can only be done from the command-line interface - e.g. through SSH. Once you're connected, you simply have to execute the following:

```bash
sudo yunohost app upgrade garradin -u https://github.com/YunoHost-Apps/paheko_ynh --debug
```

The --debug option will let you see the full output. If you encounter any issue, please report it aand paste the logs.

**Important**: After the migration, you'll have to wait a couple of minutes (at most 3 minutes) before you can start using Paheko.

## Documentation and resources

* Official app website: <https://paheko.cloud>
* Official admin documentation: <https://fossil.kd2.org/paheko/wiki?name=Documentation>
* Upstream app code repository: <https://fossil.kd2.org/paheko/dir?ci=tip>
* YunoHost documentation for this app: <https://yunohost.org/app_paheko>
* Report a bug: <https://github.com/YunoHost-Apps/paheko_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/paheko_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/paheko_ynh/tree/testing --debug
or
sudo yunohost app upgrade paheko -u https://github.com/YunoHost-Apps/paheko_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
