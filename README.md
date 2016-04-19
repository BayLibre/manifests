# Baylibre repo manifest

## Usage instruction ##

* create a project folder  e.g. ~/ACME
* enter the project folder
* call repo init as specified below

## ACME build crater (iio version)

` repo init -u https://github.com/BayLibre/manifests.git -m acme/production.xml`

## JUNO build crater

` repo init -u https://github.com/BayLibre/manifests.git -m juno/default.xml`

## POWERCI

` repo init -u https://github.com/BayLibre/manifests.git -m powerci/default.xml`

## Common Source Checkout Folder (optionnal) ##

In case you wish the different platforms to build from the same
sources/ tag, and avoid multiple git clones of u-boot and or kernel
you may pull the "common" repo.

in HOME/COMMON
` repo init -u https://github.com/BayLibre/manifests.git -m common/default.xml`

in HOME/ACME
` repo init -u https://github.com/BayLibre/manifests.git -m acme/common.xml`

in HOME/JUNO
` repo init -u https://github.com/BayLibre/manifests.git -m acme/common.xml`

etc...


