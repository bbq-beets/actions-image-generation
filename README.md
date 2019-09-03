
# GitHub Actions VM images for Hosted CI/CD

## Overview

This repo contains scripts that generate the Linux and Windows virtual machine images used by GitHub Actions for Hosted CI/CD. The images are generated using [Packer](https://www.packer.io/).

# Image contents

- [Ubuntu 16.04](images/linux/Ubuntu1604-README.md)
- [VS 2019 + Windows Server 2019](images/win/Vs2019-Server2019-Readme.md)
- [VS 2017 + Windows Server 2016](images/win/Vs2017-Server2016-Readme.md)
- [Windows Container 1803](images/win/WindowsContainer1803-Readme.md)

## Issues and requests

If you have an issue or request for an image, please create an issue in this repo. To add or change a tool yourself, see [Contributing](#contributing).

## Image generation help

### Linux

- [How to use Packer to create Linux VM images in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/build-image-with-packer)

### Windows

- [Instructions to build Windows images](/help/CreateImageAndAzureResources.md)
- [How to use Packer to create Windows VM images in Azure](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/build-image-with-packer)

## Contributing

TBD

## Legal Notices

TBD
