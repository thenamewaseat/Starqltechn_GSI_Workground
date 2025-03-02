# Starqltechn_GSI_Workground

1. Hard Press Button
Workground: Use Key Mapper to map the button to home key

2. Battery light
Use lightflow and enable root mode, Samsung root mode for LED select led_r, led_g, led_b and led_w

3.Brightness flickering
Workground: Phh Treble Settings -> Set backlight scale/max backlight level = 0

4a. USB audio play on speaker (have headphone icon)
Workground: Phh Treble Settings -> Qualcomm features -> Use alternate audio policy

4b. Cannot detect earphone (old vendor/GSI i guess?)
Workground: Use phh's fixed audio policy and put in vendor/etc

4c. Viper4android won't process on games
Workground: Disable Ultra low latency output in audio policy in <route> sink = "Wired Headphones", delete "raw" / "fast" in sources

5. Galaxy wearable doesn work
Workground: https://github.com/Linux4/GalaxyWearable
