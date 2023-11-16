# action-sign

This action allows for signing a manifest file generated by the Gluons `make manifest`.

## Inputs
## gluon-path
Path to a checked-out Gluon repository used for signing.

## container-version
Gluon [build-container](https://github.com/freifunk-gluon/gluon/pkgs/container/gluon-build) version to use.

## manifest
Path to a Gluon autoupdater manifest.

## signing-key
ECDSA key generated by [ecdsautils](https://github.com/freifunk-gluon/ecdsautils) used for signing the manifest.

## write-signature
Whether or not to append the signature to the input manifest.

## Outputs
### signature
The signature resulted from signing a given manifest with a given key.