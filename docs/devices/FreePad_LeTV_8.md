---
title: "DIYRuZ FreePad_LeTV_8 control via MQTT"
description: "Integrate your DIYRuZ FreePad_LeTV_8 via Zigbee2MQTT with whatever smart home
 infrastructure you are using without the vendors bridge or gateway."
---

*To contribute to this page, edit the following
[file](https://github.com/Koenkk/zigbee2mqtt.io/blob/master/docs/devices/FreePad_LeTV_8.md)*

# DIYRuZ FreePad_LeTV_8

| Model | FreePad_LeTV_8  |
| Vendor  | DIYRuZ  |
| Description | [LeTV 8key FreePad mod](https://modkam.ru/?p=1791) |
| Exposes | battery, action, switch_type, switch_actions, linkquality |
| Picture | ![DIYRuZ FreePad_LeTV_8](../images/devices/FreePad_LeTV_8.jpg) |

## Notes

None


## Exposes

### Battery (numeric)
Remaining battery in %.
Value can be found in the published state on the `battery` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `100`.
The unit of this value is `%`.

### Action (enum)
Triggered action (e.g. a button click).
Value can be found in the published state on the `action` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The possible values are: `*_single`, `*_double`, `*_triple`, `*_quadruple`, `*_release`.

### Switch_type (enum, button_1 endpoint)
Value can be found in the published state on the `switch_type_button_1` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_1": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_1": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_1 endpoint)
Value can be found in the published state on the `switch_actions_button_1` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_1": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_1": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_2 endpoint)
Value can be found in the published state on the `switch_type_button_2` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_2": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_2": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_2 endpoint)
Value can be found in the published state on the `switch_actions_button_2` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_2": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_2": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_3 endpoint)
Value can be found in the published state on the `switch_type_button_3` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_3": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_3": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_3 endpoint)
Value can be found in the published state on the `switch_actions_button_3` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_3": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_3": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_4 endpoint)
Value can be found in the published state on the `switch_type_button_4` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_4": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_4": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_4 endpoint)
Value can be found in the published state on the `switch_actions_button_4` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_4": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_4": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_5 endpoint)
Value can be found in the published state on the `switch_type_button_5` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_5": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_5": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_5 endpoint)
Value can be found in the published state on the `switch_actions_button_5` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_5": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_5": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_6 endpoint)
Value can be found in the published state on the `switch_type_button_6` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_6": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_6": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_6 endpoint)
Value can be found in the published state on the `switch_actions_button_6` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_6": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_6": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_7 endpoint)
Value can be found in the published state on the `switch_type_button_7` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_7": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_7": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_7 endpoint)
Value can be found in the published state on the `switch_actions_button_7` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_7": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_7": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Switch_type (enum, button_8 endpoint)
Value can be found in the published state on the `switch_type_button_8` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_type_button_8": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_type_button_8": NEW_VALUE}`.
The possible values are: `toggle`, `momentary`, `multifunction`.

### Switch_actions (enum, button_8 endpoint)
Value can be found in the published state on the `switch_actions_button_8` property.
To read (`/get`) the value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/get` with payload `{"switch_actions_button_8": ""}`.
To write (`/set`) a value publish a message to topic `zigbee2mqtt/FRIENDLY_NAME/set` with payload `{"switch_actions_button_8": NEW_VALUE}`.
The possible values are: `on`, `off`, `toggle`.

### Linkquality (numeric)
Link quality (signal strength).
Value can be found in the published state on the `linkquality` property.
It's not possible to read (`/get`) or write (`/set`) this value.
The minimal value is `0` and the maximum value is `255`.
The unit of this value is `lqi`.

## Manual Home Assistant configuration
Although Home Assistant integration through [MQTT discovery](../integration/home_assistant) is preferred,
manual integration is possible with the following configuration:


{% raw %}
```yaml
sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.battery }}"
    unit_of_measurement: "%"
    device_class: "battery"
    state_class: "measurement"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.action }}"
    enabled_by_default: true
    icon: "mdi:gesture-double-tap"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_1 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_1 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_1/set"
    command_topic_postfix: "switch_type_button_1"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_1 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_1 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_1/set"
    command_topic_postfix: "switch_actions_button_1"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_2 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_2 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_2/set"
    command_topic_postfix: "switch_type_button_2"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_2 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_2 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_2/set"
    command_topic_postfix: "switch_actions_button_2"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_3 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_3 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_3/set"
    command_topic_postfix: "switch_type_button_3"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_3 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_3 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_3/set"
    command_topic_postfix: "switch_actions_button_3"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_4 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_4 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_4/set"
    command_topic_postfix: "switch_type_button_4"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_4 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_4 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_4/set"
    command_topic_postfix: "switch_actions_button_4"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_5 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_5 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_5/set"
    command_topic_postfix: "switch_type_button_5"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_5 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_5 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_5/set"
    command_topic_postfix: "switch_actions_button_5"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_6 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_6 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_6/set"
    command_topic_postfix: "switch_type_button_6"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_6 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_6 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_6/set"
    command_topic_postfix: "switch_actions_button_6"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_7 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_7 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_7/set"
    command_topic_postfix: "switch_type_button_7"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_7 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_7 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_7/set"
    command_topic_postfix: "switch_actions_button_7"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_8 }}"
    enabled_by_default: false
    icon: "mdi:tune"

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_type_button_8 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_8/set"
    command_topic_postfix: "switch_type_button_8"
    options: 
      - "toggle"
      - "momentary"
      - "multifunction"
    enabled_by_default: false
    icon: "mdi:tune"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_8 }}"
    enabled_by_default: false

select:
  - platform: "mqtt"
    state_topic: true
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.switch_actions_button_8 }}"
    command_topic: "zigbee2mqtt/<FRIENDLY_NAME>/button_8/set"
    command_topic_postfix: "switch_actions_button_8"
    options: 
      - "on"
      - "off"
      - "toggle"

sensor:
  - platform: "mqtt"
    state_topic: "zigbee2mqtt/<FRIENDLY_NAME>"
    availability_topic: "zigbee2mqtt/bridge/state"
    value_template: "{{ value_json.linkquality }}"
    unit_of_measurement: "lqi"
    enabled_by_default: false
    icon: "mdi:signal"
    state_class: "measurement"
```
{% endraw %}

