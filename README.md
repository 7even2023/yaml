# 32wroom tutorials - yaml test files 
## fn-esp32s3 (breadboard cam)

### Freenove_Ultimate_Starter_Kit_for_ESP32-S3 FNK0082 A1B0 
<img src='ch0-001_ultimate_box_unboxed_close.jpg' width='50%'/>

### note2: fnk0082 ult. part list
<img src='ch0-002_esp32-s3_fnk0082_part_list.jpg' width='70%'/>

### note3: board + 10x led-bar + 10x 220ohm resistors 
### use GPIO5 taster2 running lights 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch0-001_esphome-web-e911d0.yaml</a>
<img src='ch0-003_ultimate_box_unboxed_board.jpg' width='50%'/>

### note4: source Freenove tutorial chapters playlist
<img src='ch0-004_esp32-s3_wroom+cam+2usb_pinout.png' width='70%'/>
https://www.youtube.com/playlist?list=PLlCFIOdyWXfXNI98tTjUfWsx7-i59nKBr

# az-esp32v4 (solded testboard dotted pcb)  
### note: source GIMP handdraw reajust real pin out chip 
<img src='ch0-101_az32_pcb_bot.jpg' width='50%'/>
<img src='ch0-102_az_32chip.png' width='50%'/>
<img src='ch0-103_az32_pcb_bot2+dotted-pcb.jpg' width='50%'/>
<img src='ch0-104_esp32-v4_wroom_pinout_az32.png' width='50%'/>
<img src='ch0-105_cb32_pcb_top.jpg' width='50%'/>
<img src='ch0-106_cb32_pcb_top+relais.jpg' width='50%'/>

# haos v11.1 dashboard home panel overview 
<img src='ch0-200_all_dht11room_esphome-haos11_sensors.png' width='70%'/>

## note: haos esphome devices panel overview
<img src='ch0-201_esp32-s3_wroom+5x-az3200x+cb32_esphome-haos11.png' width='70%'/>


# env.0 az32 = home lab (guest_room)
<img src='ch0-600_haos11_sensors_az32guest.png' width='70%'/>

### button + 4xrelais(incl led) + dht11 + ultrasonic
### note: value id temp + humi + ultraschall
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch0-000_esphome-az32.yaml</a>
<img src='ch1-000a_az32_guest.jpg' width='50%'/>

# env.1 az32001 = küche (kitchen)
<img src='ch0-601_haos11_sensors_az32001kuche.png' width='70%'/>

### button + relais(incl led) + dht11 + lcd
### note: value id temp + humi 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-001_esphome-az32001.yaml</a>
<img src='ch1-001_az32001_esphome-yaml.png' width='50%'/>
<img src='ch1-001a_az32001_kitchen.jpg' width='50%'/>
<img src='ch1-001c_lcd1602_unit_bot8574.jpg' width='50%'/>
<img src='ch1-001c_lcd1602_unit_top.jpg' width='50%'/>

# env.2 az32002 = bad (bath)
<img src='ch0-602_haos11_sensors_az32002bad.png' width='70%'/>

### button + relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-002_esphome-az32002.yaml</a>
<img src='ch1-002_az32002_esphome-yaml.png' width='50%'/>
<img src='ch1-002a_az32002_bad.jpg' width='50%'/>

# env.3 az32003 = schlafzimmer (sleeping_room)
<img src='ch0-603_haos11_sensors_az32003schlaf.png' width='70%'/>

### button + relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-003_esphome-az32003.yaml</a>
<img src='ch1-003a_az32003_schlafzimmer.jpg' width='50%'/>

# env.4 az32004 = wohnzimmer (living_room)
<img src='ch0-604_haos11_sensors_az32004wohn.png' width='70%'/>

### relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-004_esphome-az32004.yaml</a>
<img src='ch1-004a_az32004_wohnzimmer.jpg' width='50%'/>

# env.5 az32005 = flur !(todo splitt env4+5+7) wip no pics 
<img src='ch0-604_haos11_sensors_az32004wohn.png' width='70%'/>

### motion(ir) + neopixel rgb light (n.a. relais(incl led) + dht11) 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">ch1-005_esphome-az32005.yaml</a>
<img src='ch1-005a_az32005_flur.jpg' width='50%'/>

# env.6 cb32 = balkon (outside/aussen)
<img src='ch0-606_haos11_sensors_cb32balkon.png' width='70%'/>

### relais(incl led) + dht11 
### <a href="https://github.com/7even2023/yaml/blob/76fa6ba39aad9fe83afc449854af3aca2f6d9836/ch0-001_esphome-web-e911d0.yaml">chx-00x_esphome-cb32.yaml</a>
<img src='ch1-006a_cb32_aussen.jpg' width='50%'/>

wip-changelog261123-1234: 
todo fix hyperlinks in readme to yaml perma file links 
todo add v1.1 code balkon=outside/aussen flur wohnzimmer

