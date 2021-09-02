# Teleinfo-Esphome-HomeAssistant

![energy usage](https://user-images.githubusercontent.com/47485034/131806105-36fd6453-91c0-439f-b1b3-c224969fffa2.png)

## Setup the ESP
1. In [the esphome folder](https://github.com/xmow49/teleinfo-esphome-homeassistant/tree/main/esphome) choose HPHC or BASE tarrif
2. In esphome, create a new node with `esp_linky` as name
3. Copy the code, change Wifi name and password
4. Upload the code.

## Setup Home Assistant
1. Copy [the configuration](https://github.com/xmow49/teleinfo-esphome-homeassistant/blob/main/configuration.yaml) into yout config file.
2. Restart HomeAssistant

## Setup Dashbord
1. Go to `Configuration` --> `Energy`
### HCHP
2. Add `today_hp_meter`, `today_hc_meter` and add the price
### BASE
2. Add `today_base_meter`, and add the price

### Wait 1 or 2 hours to get the graphic 
