# Command Line Arguments

Modifies functionality based on the arguments passed.

Example: `java -jar drc-sim-client-x.x.jar -ip 127.0.0.1`

## IP

`-ip <hostname/ip>`

Skips connect screen and settings and attempts to connect to the provided hostname or IP address.

# Touch Controls

`--touch`

By default, the desktop does not enable virtual touch controls.

## Logging

- -d, --debug: debug logging
- -e, --extra: extra debug logging
- -f, --finer: more detailed logs
- -v, --verbose: console spam

## Beam API

**Removed in 2.0**

`-api-beam <api key>`

Enables the Beam steaming controller. This only works on the desktop client.