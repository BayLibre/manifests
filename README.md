# Baylibre repo manifest

## Usage instruction ##

* create a project folder  e.g. ~/ACME
* enter the project folder
* call repo init as specified below

## ACME build environment (iio version)

` repo init -u https://github.com/BayLibre/manifests.git -m acme/buildroot.xml`

` repo sync`

## JUNO build environment

` repo init -u https://github.com/BayLibre/manifests.git -m juno/default.xml`

` repo sync`

## POWERCI

` repo init -u https://github.com/BayLibre/manifests.git -m powerci/default.xml`

` repo sync`

etc...

## WIP Poky version of ACME software ##

If you wish to build using yocto/poky, please follow the guide from
https://github.com/BayLibre/meta-baylibre.

` repo init -u https://github.com/BayLibre/manifests.git -m acme/poky.xml`

` repo sync`
