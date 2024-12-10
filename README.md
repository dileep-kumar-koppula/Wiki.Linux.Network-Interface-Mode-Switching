Monitor/Managed Mode

- `ifconfig wlan2 down`
- `iwconfig wlan2 mode managed`
- `ifconfig wlan2 up`

You may need to restart some services that you killed:

- `service network-manager restart`
