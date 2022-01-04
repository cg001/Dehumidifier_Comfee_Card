# Dehumidifier Comfee Card

I have the Comfee [Deshumidificador MDDF-20DEN7-WF 20L/day](https://www.amazon.es/-/pt/gp/product/B07MSL8YN7) and I created a lovelace card for Home Assistant from [MauricioXavier13](https://github.com/MauricioXavier13/Dehumidifier_Comfee_Card) example but using [homeassistant-midea-dehumidifier-lan](https://github.com/nbogojevic/homeassistant-midea-dehumidifier-lan) integration.

![example3](/assets/Example_3.jpg)

## Home Assistant Cards, Configuration and information

### Pre-requisites

  - HACS Custom integration
    - homeassistant-midea-dehumidifier-lan | https://github.com/nbogojevic/homeassistant-midea-dehumidifier-lan

  - HACS Custom-Cards
    - custom:multiple-entity-row | https://github.com/benct/lovelace-multiple-entity-row
    - custom:button-card | https://github.com/custom-cards/button-card
    - custom:text-divider-row | https://github.com/iantrich/text-divider-row
    - custom:paper-buttons-row | https://github.com/jcwillox/lovelace-paper-buttons-row
    - card-tools | https://github.com/thomasloven/lovelace-card-tools

### Use the card   

If you are using the same dehumidifier model/brand you just need to copy [all the card code](Dehumidifier_Comfee_Card.yaml) and replace the entity_id by your own.

Entities to replace:

- `humidifier.dehumidifier_suite`
- `sensor.dehumidifier_suite_humidity`
- `binary_sensor.dehumidifier_suite_defrosting`
- `sensor.dehumidifier_suite_temperature`
- `binary_sensor.dehumidifier_suite_tank_full`
- `binary_sensor.dehumidifier_suite_replace_filter`
- `fan.dehumidifier_suite_fan`

### Examples

![example2](/assets/Example_2.jpg)

https://user-images.githubusercontent.com/74264882/111458565-7a3ddb00-8711-11eb-9adb-d3d79542a32d.mp4


https://user-images.githubusercontent.com/74264882/111458584-7f9b2580-8711-11eb-918c-27fb9ca7ebe4.mp4
