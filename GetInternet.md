# Connecting to the internet

## Connecting to the internet

If you are on Ethernet, you can probably skip this stage.

### WiFi networks

Open the IWD controller with

`iwctl`

You are now in IWCTL. Begin by checking what your device is.

`[iwd]# device list`

Most likely it will be `wlan0`.

Now we will power on the device & adapter.

`[iwd]# device <name> set-property Powered on`

`[iwd]# adapter <adapter> set-property Powered on`

Optionally, run these commands to get the WiFi networks

`[iwd]# station <device name> scan`
`[iwd]# station <device name> get-networks`

Then to connect run

`[iwd]# station <device name> connect <Network name/SSID>`

Congrats, you have connected to the internet.

### Mobile broadband modem

This section may need editing.

Simply just run

`$ $ mmcli -m MODEM_INDEX --simple-connect="apn=<myisp>,user=<user_name>,password=<password>"`

to connect. If you don't need a username or password just use

`mmcli -m MODEM_INDEX --simple-connect="apn=<myisp>"`

to connect.

You should be connected now. Move onto this:

[Installing Polaris Linux](https://polaris-linux-distro.github.io/handbook/Installation) 