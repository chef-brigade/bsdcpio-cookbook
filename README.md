# bsdcpio

[![Cookbook Version](https://img.shields.io/cookbook/v/bsdcpio.svg)](https://supermarket.chef.io/cookbooks/bsdcpio)
[![Build Status](https://img.shields.io/circleci/project/github/sous-chefs/bsdcpio/master.svg)](https://circleci.com/gh/sous-chefs/bsdcpio)

## Description

Installs bsdcpio, which uses libarchive to support working with tar, pax, cpio, zip, jar, ar, and ISO 9660 cdrom images.

## Requirements

### Platform

The following platforms have been tested with this cookbook:

- Ubuntu

### Chef

- Chef 12.1+

### Cookbooks

- none

## Usage

Place `recipe[bsdcpio::default]` in the `run_list` of your node or role.

## License and Author

Author:: Joseph Anthony Pasquale Holsten (joseph@josephholsten.com) [![endorse](http://api.coderwall.com/josephholsten/endorsecount.png)](http://coderwall.com/josephholsten)

Copyright:: 2013, Joseph Anthony Pasquale Holsten

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
