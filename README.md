# Lepton

## Setting Up Flir Lepton

- Connect Flir Lepton to Raspberry Pi headers

![alt text](https://cdn.sparkfun.com/assets/learn_tutorials/3/5/9/RPi-FLIR-Diag-FIXED.png) </br>
\* CS should be across from CLK, not across and down one pin

- Enable SPI and I2C interfaces

```
sudo raspi-config
```

## Setting Up Code

- Install pylepton

```
git clone https://github.com/groupgets/pylepton.git

cd pylepton

git checkout lepton3-dev

sudo python setup.py install
```

- Copy Lepton.html and camera_stream.sh to robo-html

## How to use

- Run camera_stream.sh in side of robo-html

```
./camera_stream.sh
```

- Open up web browser  and go to ip/Lepton.html
