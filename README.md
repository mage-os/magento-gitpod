# Mage-OS Magento 2 Gitpod Cloud Development Environment

This repository contains a Gitpod configuration for a Magento 2 cloud development environment using Mage-OS as the composer repository.

This allows for installing Magento 2 using the Mage-OS Mirror or the nightly build (see: [https://mage-os.org/distribution](https://mage-os.org/distribution) for more details).
  
# Getting Started
Once the Gitpod browser extension is installed [Download Extension](https://www.gitpod.io/docs/browser-extension), click the Gitpod button in this repo to get started with a blank Magento 2 enviroment. Use the `mage-os-mirror` (default) branch for the Mage-OS Mirror and the `mage-os-nightly` branch for the nightly builds.

Or simply visit either of the following URLs:
* Mirror: [https://gitpod.io/#https://github.com/mage-os/magento-gitpod](https://gitpod.io/#https://github.com/mage-os/magento-gitpod)
* Nightly Build: [https://gitpod.io/#https://github.com/mage-os/magento-gitpod/tree/mage-os-nightly](https://gitpod.io/#https://github.com/mage-os/magento-gitpod/tree/mage-os-nightly)

# Configuring Magento and the Server Env Versions
All configuration options including Magento versions and Admin login are found here [.gitpod.Dockerfile](https://github.com/mage-os/magento-gitpod/blob/mage-os-mirror/.gitpod.Dockerfile). 


# Credit
Based on the original Gitpod config produced by:
* https://github.com/develodesign/magento-gitpod
* https://github.com/nemke82/magento2gitpod
