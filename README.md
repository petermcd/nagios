# Nagios

This repository servers as a collection of Nagios check plugins.

The plugins are somewhat sparse at the moment but will grow over time.

## Disclaimer

The plugins are very rough and ready for the moment, use at your own risk
and a pull request with any improvements is always appreciated.

## Plugins

### ssh_cpu

Simple bash script that obtains the current load of a given host

* -w - At what load level a warning is triggered (defaults 0.5)
* -c - At what load level critical is triggered (defaults 0.8)
* -H - The host to check.
* -u - Specifies the desired ssh user to connect to. Defaults to current username
* -4 - Specify to use ipv4 (default)
* -6 - Specify to use ipv6
* -h - Display help information