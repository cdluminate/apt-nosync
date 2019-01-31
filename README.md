apt-nosync
==========

Accelerate APT and DPKG with eatmydata

This package will divert apt and dpkg executables and replace them with
eatmydata-based wrapper scripts. This would result in significantly faster apt
and dpkg actions, and some side effects.

## Building

```
dpkg-buildpackage -us -uc
```
