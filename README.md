# wine-fsr
A script to provide easier use setting wine fsr options and configuration with proton/wine

# NOTE: ONLY WORKS WITH WINE/PROTON!

## Usage: wine-fsr [OPTION]...
#### Resolution options for AMD FSR: (1080p example)
  
  -u, --ultra           Ultra Quality, 1.3x scale: (1476x830)
  
  -q, --quality         Quality, 1.5x scale: (1280x720)
  
  -b, --balanced        Balanced, 1.7x scale: (1129x635)
  
  -p, --performance     Performance, 2x scale: (960x540)
  
  -c, --custom          Set custom resolution mode.


#### Sharpness options for AMD FSR:

  0, Sharpest
  
  1, Sharper
  
  2, Sharp
  
  3, Soft
  
  4, Softer
  
  5, Softest

## Config file:
  Place config file in: `$HOME/.config/wine-fsr/wine-fsr.conf`
  
  Place per game config files in: `$HOME/.config/wine-fsr/[game program name].conf`
  
  ### Note: Config file options are overridden by options provided at runtime if present.
