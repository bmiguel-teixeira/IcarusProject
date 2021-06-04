1. Enable i2c
    * sudo raspi-config
    * Interfacing Options
    * I2C
    * Check with `sudo ls -la /dev/i2c*`

2. Install
```
sudo apt-get update
sudo apt-get install -y python-smbus i2c-tools
```