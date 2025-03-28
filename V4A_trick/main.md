# V4ARE in 192000hz

Feature: 
- audio route to hifi-playback in USB audio (usb-headset)
- 192000 sampling rate and 32 bit audio in V4ARE on 3.5mm jack (not sure if really real)

concepts:
- Vendor audio policy have hifi-playback usb-headset, but mixer path doesnt have hifi-playck in usb-headset, need to manually create one. (create pathname "hifi-playback usb-headset" ctl="USB_AUDIO_RX Audio Mixer Multimedia2" in mixer path)
- change sampling rate to 192000 in mixport "primary output" (change AUDIO_FORMAT to 32 bit and add 192000 in sampling rate)
- only tested in latest S9 vendor (G9600ZCS9FVA4)
