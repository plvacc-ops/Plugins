# Polish vACC - Plugin Configuration

Configurations for both officially used and additional plugins for Polish vACC vATCOs

## Plugins
- [AMAN](https://github.com/EvenAR/euroscope-aman)
- [CCAMS](https://github.com/kusterjs/CCAMS)
- [CDM](https://github.com/rpuig2001/CDM)
- [GroundRadar](https://vats.im/GRplugin)
- [TopSky](https://vats.im/TopSkyPlugin)
- [VCH](https://github.com/DrFreas/VCH)
- [vSMR](https://github.com/plvacc-ops/vSMR)
- [vStrips](https://www.vstrips.uk/download)

## TopSky & RDF 
When using separate **RDF** plugin alongside **TopSky**, they can lead to **EuroScope** crashes, therefore you should update `TopSkySettings.txt`:

```
RDF_Mode=-1
```

## vSMR
When using **Polish vACC vSMR**, you should update profile filters:

```
"filters": {
    "hide_above_alt": 10000,
    "hide_above_spd": 400,
    "radar_range_nm": 250,
    "night_alpha_setting": 110,
    "pro_mode": false
},
```