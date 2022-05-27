# smart-python-launcher

## Dedication: In Honor of Brian Hardie

This launcher is not for the faint of heart. It replaces the system Python executable with a script that by default, still calls the system Python executable, but can also be directed to call other specific Python executables. This allows you to overcome problems with third-party packages that hard-code a hash-bang line pointing at the system PPython directly and require a Python version that is different from the system Python version.
