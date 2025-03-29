# V4ARE in 192000hz

**Feature:**
- audio route to hifi-playback in USB audio (usb-headset, need DAC support)
- 192000 sampling rate and 32 bit audio in V4ARE on 3.5mm jack (not sure if really real)

**How to install:**
- put the file to /vendor/etc/ (Please backup first)

**concepts:**
- Vendor audio policy have hifi-playback usb-headset, but mixer path doesnt have hifi-playck in usb-headset, need to manually create one. (create pathname "hifi-playback usb-headset" ctl="USB_AUDIO_RX Audio Mixer Multimedia2" in mixer path)
- change sampling rate to 192000 in mixport "primary output" (change AUDIO_FORMAT to 32 bit and add 192000 in sampling rate)
- only tested in latest S9 vendor (G9600ZCS9FVA4)

**Screenshots:**
![Screenshot_20250328-183721_MatLog](https://github.com/user-attachments/assets/4673a674-cc8a-4411-bba5-75220ac9416c)
![Screenshot_20250328-202437_ViPER4Android FX](https://github.com/user-attachments/assets/074c912c-9bf2-4f82-a32c-acc4f7859976)
![Screenshot_20250328-200451_MT管理器](https://github.com/user-attachments/assets/4744db0f-c13c-42ee-bb03-d69333b7fcf5)


