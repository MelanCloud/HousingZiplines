# HousingZiplines
An extremely dynamic and configurable zipline function for Hypixel Housing.

Requires [HTSL](https://github.com/BusterBrown1218/HTSL)

### Setup:
**Destination**
- var zip/x = destination x
- var zip/y = destination y
- var zip/z = destination z

**Initiation**
- var zip/active = 1

### Optional Setup:
**Slack Factor** var zip/slack (default: 5) [range: -inf to inf]
- -x : works intuitively (goes upwards)
- 1 : extremely light slack
- 5 : normal slack
- 10 : heavy slack

**Magnitude Factor** var zip/mag (10) [-inf to inf]
- <-5 : may cause issues
- -x : works intuitively (inverse slope acceleration) 
- 1 : base acceleration
- 10 : x10 slope acceleration
- 100 : x100 slope acceleration

**Decay Factor** var zip/decay (10) [-inf to inf]
- -x : works intuitively (reverses decay)
- 1 : no decay
- 10 : normal decay
- 50 : extremely light decay
- \>50 : may cause issues

**Initial Speed** var zip/speed (1000) [0+]
- -x : does not support negative values
