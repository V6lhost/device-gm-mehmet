## postmarketOS device package of gm-mehmet

How to use:
- clone this repository into `cache_git/pmaports/device/testing/` (It's under `~/.local/var/pmbootstrap/` directory by default)
- run `pmbootstrap init` and select gm-mehmet
- run `pmbootstrap install` and then `pmbootstrap export`
- your boot and rootfs image is now available under `/tmp/postmarketOS-export/` folder

Warning: support for gm-mehmet has not yet been added to linux-postmarketos-exynos4 kernel package. but kernel source and building instructions are available on postmarketos page. 
