
![Logo][logo]

# Hassio add-on Repository
This repository contains Hass.io add-ons. All add-on in this repository is Tested on Hass.io, hassbian installation is not supported.

### Installation
Add the repository URL via the Hassio Add-on Store Tab: `https://github.com/homematevn/ha`

Hass.io Add-on install instructions [here](https://www.home-assistant.io/hassio/installing_third_party_addons/)

### Updating
Enable `Auto update` on the desired add-on or browse Hassio Add-on Store Tab to check for update

## Add-ons in this Repository

#### Backup Hass.io to Google Drive
This add-on will upload files from your hass.io backup folder (.tar files created by the hass.io SnapShot) to your Google Drive.

You can find the [details here](https://github.com/ttvt/hassio/tree/master/googlebackup).

#### Zigbee2MQTT
Communication with zigbee endpoint using CC2530/ CC2531 chip.
You will need a Zigbee module flashed coordinator firmware in order to work.

You can find the [details here](https://github.com/ttvt/hassio/tree/master/zigbee2mqtt).

#### Component Store
Manage all your custom components and plugins (lovelace elements) with ease.

You can find the [details here](https://github.com/ttvt/hassio/tree/master/componentstore).

# Custom Component
**NOTICE**: It's recommend to use **Component Store Add-on** to install `custom components`. Component installed manually will not be mananged in component store.

If you found useful component and want to share, don't hesitate let us know.

### Simple Installation
1. Make sure you've the [Component Store](https://github.com/ttvt/hassio/tree/master/componentstore) installed and working.
2. Navigate to the Store (on the menu bar), select Store 
3. Search and select **component** you want and install.
4. Refer to component documents for configure and usage
5. Restart Home-Assistant.

### Manual Installation
1. Download component and extract to `component_name` folder
2. Create a new folder called `component_name` inside your ha_config_dir/custom_components directory and copy the all the files from `component_name` to it.
3. Refer to component documents for configure and usage
4. Restart Home-Assistant.

### Updating
Use Custom Component Store to update your card

## Useful Components in this Store

#### SmartIR
Modify from SmartIR for better service `media_player.select_source` 

You can find the [details here](https://github.com/MagnetVN/smartIR)

#### Zing MP3
Play media on zing.mp3.vn. Offer 2 services: `zing_mp3.play` and `zing_mp3.play_top100`

You can find the [details here](https://github.com/MagnetVN/zing_mp3)



# Lovelace UI Custom Card (Plugin)
If you found useful card and want to share, don't hesitate let us know.

### Installation
1. Make sure you've the [Component Store](https://github.com/ttvt/hassio/tree/master/componentstore) installed and working.
2. Navigate to the Store (on the menu bar), select Store 
3. Search and select **cards** you want and install.
4. Add reference to **cards** inside your `ui-lovelace.yaml` or at the top of the *raw config editor UI*. Instruction 
shown when you install card. For ex, when install mini-graph-card, you need to add:

  ```yaml
  resources:
    - type: module
      url: /community_plugin/mini-graph-card/mini-graph-card.js
  ```
  
5. Restart Hass UI, you can now use use the `custom-card`.

### Updating
Use Component Store to update your card

*You may need to empty the browsers cache if you have problems loading the updated card.*

## Some useful Cards in this Repository

### Mini Graph Card
You can find the [details here](https://github.com/kalkih/mini-graph-card)
### Simple Thermostat
You can find the [details here](https://github.com/nervetattoo/simple-thermostat)
### Mini Media Player
You can find the [details here](https://github.com/kalkih/mini-media-player)

# Credit

This repository is credit to MagnetVN, LLC

Copyright (c) 2019, ttvtien

[logo]: https://github.com/HomeMateVN/ha/raw/master/images/homemate.png