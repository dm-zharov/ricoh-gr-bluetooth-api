# RICOH GR Bluetooth API

## Overview 

An **unofficial** list of characteristics and their effects. The supported models are refered to as below. There are certain functional differences between each model.

- RICOH GR II / GR III / GR IIIx
- RICOH G900 SE / WG-M2
- PENTAX K1 / K-3 Mark III / K-3 Mark III Monochrome / K70 / KF / KP

Source:
- Reverse Engineering  
- [RICOH THETA API Specifications](https://github.com/ricohapi/theta-api-specs): API for 360° cameras

**Use at your own risk.**

## Content

### Developer Guide

- [Characteristics list](./characteristics_list.md)  
- [Bluetooth 4.2 Core Specifications](https://www.bluetooth.org/DocMan/handlers/DownloadDoc.ashx?doc_id=286439&_ga=2.97979420.260081372.1496207139-937189733.1496207139)

### API Reference

#### Camera Information

[Firmware Revision String](./camera_information/firmware_revision_string.md)  
[Manufacturer Name String](./camera_information/manufacturer_name_string.md)  
[Model Number String](./camera_information/model_number_string.md)  
[Serial Number String](./camera_information/serial_number_string.md)  
[Bluetooth Device Name](./camera_information/bluetooth_device_name.md)  
[Bluetooth MAC Address String](./camera_information/bluetooth_mac_address_string.md)

#### Camera

[Camera Service Notification](./camera/camera_service_notification.md)  
[Camera Power](./camera/camera_power.md)  
[Battery Level](./camera/battery_level.md)  
[Date Time](./camera/date_time.md)  
[Operation Mode](./camera/operation_mode.md)  
[Operation Mode List](./camera/operation_mode_list.md)  
[GEO Tag](./camera/geo_tag.md)  
[Storage Information](./camera/storage_information.md)  
[File Transfer List](./camera/file_transfer_list.md)  
[Power Off During File Transfer](./camera/power_off_during_file_transfer.md)  
[Grad ND](./camera/grad_nd.md)  

#### Shooting

[Shooting Service Notification](./shooting/shooting_service_notification.md)  
[High Frequency Shooting Service Notification](./shooting/high_frequency_shooting_service_notification.md)  
[Shutter Speed](./shooting/shutter_speed.md)  
[Shutter Speed List](./shooting/shutter_speed_list.md)  
[Aperture](./shooting_service)  
[Aperture List](./shooting/aperture_list.md)  
[ISO Sensitivity](./shooting/iso_sensitivity.md)  
[ISO Sensitivity List](./shooting/iso_sensivity_list.md)  
[Exposure Compensation](./shooting/exposure_compensation.md)  
[Exposure Compensation List](./shooting/exposure_compensation_list.md)  
[White Balance](./shooting/white_balance.md)  
[White Balance List](./shooting/white_balance_list.md)  
[Drive Mode](./shooting/drive_mode.md)  
[Drive Mode List](./shooting/drive_mode_list.md)  
[Shooting Mode](./shooting/shooting_mode.md)  
[Shooting Mode List](./shooting/shooting_mode_list.md)  
[Metering mode](./shooting/metering_mode.md)  
[Capture Mode](./shooting/capture_mode.md)  
[File Type](./shooting/file_type.md)  
[File Type List](./shooting/file_type_list.md)  
[JPEG Size](./shooting/jpeg_size.md)  
[Movie Configuration](./shooting/movie_configuration.md)  
[Operation Request](./shooting/operation_request.md)  
[Focus Mode](./shooting/focus_mode.md)  
[Focus Setting List](./shooting/focus_setting_list.md)  
[Auto Focus Status](./shooting/auto_focus_status.md)  
[Capture Status](./shooting/capture_status.md)  
[Shot Count](./shooting/shot_count.md)  
[Self Timer](./shooting/self_timer.md)

#### GPS Control Command

[GPS Information](./gps_control_command/gps_information.md)  

#### WLAN Control Command

[Network Type](./wlan_control_command/network_type.md)  
[SSID](./wlan_control_command/ssid.md)  
[Passphrase](./wlan_control_command/passphrase.md)  
[Channel](./wlan_control_command/channel.md)  

#### Bluetooth Control Command

[BLE Enable Condition](./bluetooth_control_command/ble_enable_condition.md)  
[Paired Device Name](./bluetooth_control_command/paired_device_name.md)  