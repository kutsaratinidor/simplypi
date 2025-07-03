# SimplyPi: Lightweight Raspberry Pi B+ Image

## About
A minimal Buildroot-based image for Raspberry Pi B+ with AdGuard Home and Tailscale pre-installed. Goal is to make use of old Pi B+ I have lying around without installing a full raspbian OS.

## Download
Get the compressed image from the `images/` directory. Decompress the .gz file to get the image file.

## Flashing Instructions
```sh
sudo dd if=images/simplypi-rpi-bplus.img of=/dev/rdiskN bs=4M status=progress
```
Replace `/dev/rdiskN` with your SD card device.

## Default Access
- AdGuard Home: http://<pi-ip>:3000 - For AdGuard Home initial setup
- Tailscale: See [Tailscale docs](https://tailscale.com/kb/)

## Notes
- Set root password after first boot.
- For support, open an issue in this repo.
