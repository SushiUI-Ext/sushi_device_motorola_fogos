# SushiUI tree for Motorola Moto G34 5G (fogos)
(for SushiUI Extended)

Configurations for this SushiUIext device written in Makefile and Shell.

![fogos](https://raw.githubusercontent.com/SushiUI-Ext/sushi_device_motorola_fogos/refs/heads/main/fogos.png)

Copyright © 2023 Motorola Mobility LLC. All rights reserved.

Copyright (c) 2026 SushiUI / SushiUI Extended. All rights reserved.

---
If you are installing SushiUI on your device,
```Code
* We not responsible for bricked devices, dead SD cards, thermonuclear war, 
* or you getting fired because the alarm app failed. Please do some research 
* if you have any concerns about features included in this module
* before flashing it! YOU are choosing to make these modifications, and if
* you blame us in any way for what happens to your device, we will laugh at you.
* BOOM! goes the dynamite
```

## Building on fogos
```bash
. ./envsetup.sh
smake
```

Build options:
```bash
smake MAINTAINER=name
smake OFFICIAL=1 MAINTAINER=name
```

`MAINTAINER` defaults to the output of `whoami`. `OFFICIAL` defaults to `0`.

This device tree is untested on real hardware.

If you want to see [Moto G45 5G](https://m.gsmarena.com/motorola_moto_g45-13267.php) tree, see [sushi_device_motorola_fogos2](https://github.com/SushiUI-Ext/sushi_device_motorola_fogos2)
# Maintainers of this device

[rebangkkuser](https://github.com/rebangkkuser)
