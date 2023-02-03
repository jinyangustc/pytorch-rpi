# Pytorch 1.13.1 for Raspberry Pi 3B+

On Raspberry Pi:

```bash
$ uname -a
Linux rs2.local 5.10.103-v7+ #1529 SMP Tue Mar 8 12:21:37 GMT 2022 armv7l GNU/Linux

$ lsb_release -a
No LSB modules are available.
Distributor ID: Raspbian
Description:    Raspbian GNU/Linux 10 (buster)
Release:        10
Codename:       buster
```

Pytorch version:

```
ARG TORCHVER=v1.13.1
ARG TORCHVISIONVER=v0.14.1
ARG TORCHAUDIOVER=v0.13.1
ARG NUMPYVER=1.21.6
```
