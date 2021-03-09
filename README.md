# rpirepo

### Setup

```
ssh-keygen
sudo timedatectl set-timezone UTC
timedatectl
```

#### Start-up

Edit your [etc/rc.local]

## GPIOs

### Basic

```
echo 7 > /sys/class/gpio/export 
echo out > /sys/class/gpio/gpio7/direction 
echo 1 > /sys/class/gpio/gpio7/value
```

### Buttons



### LCD

https://www.mbtechworks.com/projects/drive-an-lcd-16x2-display-with-raspberry-pi.html

## Straming using motion

https://www.instructables.com/How-to-Make-Raspberry-Pi-Webcam-Server-and-Stream-/

See files in [etc/motion] and [etc/default].
