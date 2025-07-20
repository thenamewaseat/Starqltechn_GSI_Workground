# Starqltechn(SM-G9600)_GSI_Workground

 - **Hard Press Button**\
Workground: Use Key Mapper to map the button to home key

- **Battery light**\
Use lightflow and enable root mode, Samsung root mode for LED select led_r, led_g, led_b and led_w

- **Brightness flickering**\
Workground: Phh Treble Settings -> Set backlight scale/max backlight level = 0

- **USB audio play on speaker (have headphone icon)**\
Workground: Phh Treble Settings -> Qualcomm features -> Use alternate audio policy

- **Cannot detect earphone (old vendor/GSI i guess?)**\
Workground: Use phh's fixed audio policy and put in vendor/etc

- **Viper4android won't process on games**\
Workground: Disable Ultra low latency output in audio policy in <route> sink = "Wired Headphones", delete "raw" / "fast" in sources

- **Galaxy wearable doesn work**\
Workground: https://github.com/Linux4/GalaxyWearable

- **Device model show as TrebleDroid GSI**\
Workground: install TrebleGSIProps in KSU

- **Force system RW**\
backup old system, install a system that is rw and restore old system in twrp (tested in EvoX 10.3.1)

- **GSI that boots**\
A15: Evolutionx 10.3.1 (Jan1 G9600ZCS9FVA4)

- **GSI that doesn't boots**\
Android 16 qpr0 (possibly because my vendor is Jan1 G9600ZCS9FVA4, May1 G9600ZCU9FVE3 should can boot)
