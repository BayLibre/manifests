# Baylibre repo manifest

## Usage instruction ##

* create a project folder  e.g. ~/powerci
* enter the project folder
* call repo init as specified below

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

## POWERCI

` repo init -u https://github.com/BayLibre/manifests.git -m powerci/default.xml`

## ACME build crater

### production grade (iio)

` repo init -u https://github.com/BayLibre/manifests.git -m acme/production.xml`

### sigrok-iio dev

` repo init -u https://github.com/BayLibre/manifests.git -m acme/sigrok-iio.xml`

## JUNO build crater

` repo init -u https://github.com/BayLibre/manifests.git -m juno/default.xml`

## ODROID C1p build crater

` repo init -u https://github.com/BayLibre/manifests.git -m odroid/default.xml`

