# Dehumidifier Comfee Lovelace Card - Home Assistant

I have the Comfee [Deshumidificador MDDF-20DEN7-WF 20L/day](https://www.amazon.es/-/pt/gp/product/B07MSL8YN7) and I created a lovelace card for Home Assistant from [MauricioXavier13](https://github.com/MauricioXavier13/Dehumidifier_Comfee_Card) example but using [homeassistant-midea-dehumidifier-lan](https://github.com/nbogojevic/homeassistant-midea-dehumidifier-lan) integration.

![animation](/assets/Dehumidifier_Animation.gif)

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

![example1](/assets/Example_1.png) 
![example1](/assets/Example_2.png)
