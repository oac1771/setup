### Install OS
[imager](https://www.raspberrypi.com/documentation/computers/getting-started.html#raspberry-pi-imager)

### Discover Raspberry PI IP
Use [mdns](https://www.raspberrypi.com/documentation/computers/remote-access.html#resolve-raspberrypi-local-with-mdns)

Ex:
```
ping raspberrypi.local
```

`raspberrypi.local` is the hostname of pi

### SSH into Raspberry PI

```
ssh <username>@raspberrypi.local
```



### File Sharing
https://www.raspberrypi.com/documentation/computers/remote-access.html#scp

### shut down using ssh
```
sudo shutdown -h now
```