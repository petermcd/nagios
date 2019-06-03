# Nagios

This repository servers as a collection of Nagios check plugins.

The plugins are somewhat sparse at the moment but will grow over time.

## Disclaimer

The plugins are very rough and ready for the moment, use at your own risk
and a pull request with any improvements is always appreciated.

## Plugins

### ssh_cpu

Simple bash script that obtains the current load of the host

* -w - At what load level a warning is triggered (defaults 0.5)
* -c - At what load level critical is triggered (defaults 0.8)
* -h - Display help information

### ssh_file_system_usage

Simple bash script that alerts if the usage level of any mount
point exceeds the critical or warning level.

* -w - At what usage level a warning is triggered (defaults 70)
* -c - At what usage level critical is triggered (defaults 80)
* -h - Display help information