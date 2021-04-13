# keyrock-theme-pdc
Theme for Packet Delivery Co. IDP

## Usage
Creates directories for the theme and the img files within the container file system at:
```shell
/themes/i4trust-pdc
/img/i4trust-pdc
```
The above directories should be mounted to external volumes when running this container.

When running Keyrock via Docker (or K8s), above created external volumes should be mounted to the Keyrock 
container at the corresponding places in order to be able to use the theme and img files.
