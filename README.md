# wtfutil Snap Package [![CircleCI Build Status](https://circleci.com/gh/felicianotech/snap-wtfutil.svg?style=shield)](https://circleci.com/gh/felicianotech/snap-wtfutil) [![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/felicianotech/snap-wtfutil/master/LICENSE)

WTF is a personal information dashboard for your terminal, developed for those who spend most of their day in the command line.

It allows you to monitor systems, services, and important information that you otherwise might keep browser tabs open for, the kinds of things you don’t always need visible, but do check in on every now and then.

This repository provides the source code for the `wtfutil` snap which is available in the [Snapcraft Store](https://snapcraft.io/wtfutil).
The snap is maintained by [@FelicianoTech](https://twitter.com/FelicianoTech) meanwhile the code for `wtfutil` itself is maintained by a different party.
The upstream repository can be found [here](https://github.com/wtfutil/wtf).


## Installation

`wtfutil` can be installed via snap on Ubuntu 18.04, Ubuntu 19.04+, elementary OS 5.0+, and many other Linux distros with `snapd` installed by running:

```
sudo snap install --classic wtfutil
```

If you don't have the `snap` command available, you might be able to find instructions for your distro [here](https://docs.snapcraft.io/core/install).
Otherwise, the official wtfutil project offers many other ways to install on their [Readme page](https://github.com/wtfutil/wtf#installing).


## Usage

Basic usage of `wtfutil` is simple, run the command in a terminal:

```
wtfutil
```

Configuring `wtfutil` in order to have custom dashboard is a bit harder.
Their website has a guide for configure that you can check out [here](https://wtfutil.com/configuration/).


## Development

This snap is built with [Snapcraft](https://snapcraft.io/) v3.8+.

On Ubuntu:

```
sudo snap install --classic snapcraft
snapcraft
```


## License

The code for this snap is licensed under the MIT license.
The code for `wtfutil` itself is licensed under the Mozilla Public License 2.0.
This repo's license can be found [here](./LICENSE) while the license for `wtfutil` can be found [here](https://github.com/wtfutil/wtf/blob/master/LICENSE.md).
