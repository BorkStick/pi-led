# pi-led

## Info
python script for running a neopixel off of a raspberry pi

## Setup
install python and pip
```
sudo apt-get install -y python3 python3-pip
```

install neopixel library
```
sudo pip3 install -y rpi_ws281x adafruit-circuitpython-neopixel
```
download pi-led
```
wget https://lab.borkslash.com/BorkStick/pi-led/raw/master/pi-led
```
make it executable
```
chmod +x pi-led
```
move it to the bin dir so it can be used
```
sudo mv pi-led /bin/
```

## Usage

sudo pi-led [COLOR]
```
sudo pi-led blue
```