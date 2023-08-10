---
title: OSC (Open Sound Control)
description: Instructions on how to use OSC (Open Sound Control) to send Home Assistant.
ha_category:
  - Presence Detection
ha_iot_class: Local Push
ha_release: 0.01
ha_domain: osc
ha_platforms:
  - sensor
ha_integration_type: integration
---

The `OSC` integration allows Home Assistant to communicate with devices that implement the OSC (Open Sound Control) Protool. Currently, only Int and Float type messages are suported.


## Usage

To use this integration, setup one more devices and call a service by specifying the entity and messasge to send to the entity.
