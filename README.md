# SimplyPi: Lightweight Raspberry Pi B+ Image

## About
A minimal Buildroot-based image for Raspberry Pi B+ with AdGuard Home and Tailscale pre-installed.

## Download
Get the image from the `images/` directory.

## Flashing Instructions
```sh
sudo dd if=images/simplypi-rpi-bplus.img of=/dev/rdiskN bs=4M status=progress
```
Replace `/dev/rdiskN` with your SD card device.

## Default Access
- AdGuard Home: http://<pi-ip>:3000
- Tailscale: See [Tailscale docs](https://tailscale.com/kb/)

## Notes
- Change default passwords after first boot.
- For support, open an issue in this repo.