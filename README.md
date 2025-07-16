# HousingZiplines
An extremely dynamic and configurable zipline function for Hypixel Housing.

Requires [HTSL](https://github.com/BusterBrown1218/HTSL)

### Setup:
> - var zip/x = destination x
> - var zip/y = destination y
> - var zip/z = destination z
> - var zip/active = 1

### Optional Setup:
> var zip/slack = slack factor (default: 5)
> - -x : Works intuitively (goes upwards)
> - 0 : no slack
> - 1 : extremely light slack
> - 5 : normal slack
> - 10 : heavy slack

ℹ️﻿ default: 5, factors of 5
⚠️ higher values may *rarely* cause issues

> var zip/mag = magnitude factor
> - -x : works intuitively (inverse slope acceleration) 
> - 0 : base acceleration
> - 10 : x10 slope acceleration
> - 100 : x100 slope acceleration

ℹ️ default: 10, factors of 5
⚠️ higher values may *rarely* cause issues

> var zip/decay = decay factor (default: 10) [-inf to inf]
> - -x : works intuitively (reverses decay)
> - 0 : no decay
> - 10 : normal decay
> - 100 : heavy decay

ℹ️﻿ default: 10, all numbers
