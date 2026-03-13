What You Are Building
Clipod is a clip-on Linux audio player with a 1.3-inch OLED, six physical buttons, a 3.5mm headphone jack, a microSD slot, and Wi-Fi. It plays user-owned music files from the SD card and streams audio from YouTube over Wi-Fi. It requires no phone during use. It has no subscriptions. It costs around $65 at retail.
The software is fully open source. The YouTube streaming is handled by yt-dlp and ffmpeg, operated by the user for personal use. The companion app is a file transfer tool. No audio is permanently downloaded from YouTube in the default firmware.
The legal risk is low because the product is open source, non-commercial in its software, and positions YouTube streaming as a personal-use client rather than a piracy tool. The hardware sale is the business.
The development path starts with a Raspberry Pi Zero 2W running all the software, then moves to a custom PCB, then to a crowdfunded production run.
The one thing to build first
Get MPD + yt-dlp + ffmpeg + an SSD1306 OLED + 6 GPIO buttons working on a Raspberry Pi Zero 2W. Everything else follows from that working prototype.


