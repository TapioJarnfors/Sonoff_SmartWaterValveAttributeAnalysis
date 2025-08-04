# Sonoff Smart Water Valve Attribute Analysis

[![Wiki Documentation](https://img.shields.io/badge/Documentation-Wiki-blue)](https://github.com/TapioJarnfors/Sonoff_SmartWaterValveAttributeAnalysis/wiki)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Overview
This wiki provides following resources for users and developers working with the Sonoff Smart Water Valve and Zigbee2MQTT:
### Event Timeline Analysis 
Event Timeline Analysis with detailed analysis of the event timeline for the Sonoff Smart Valve, focusing on both quantitative and timed irrigation cycles. The analysis is based on packet captures, highlighting key events and their corresponding attributes.
### Custom Attribute Converter Guide
Guide demonstrates how to create an external converter for a Zigbee device with manufacturer-specific attributes, using Wireshark and Zigbee2MQTT logs for development and testing. The custom converter's main job is to extract and parse relevant information from the Zigbee messages received by Zigbee2MQTT (such as attribute reports or read responses), then format and expose that data in a way that Zigbee2MQTT and Home Assistant can use. 

### Key Findings
- **Low Flow Behavior**: Documents valve operation below specified range (0.07 m³/h vs minimum 0.1 m³/h)
- **Packet Analysis**: Includes Wireshark captures and decoded Zigbee clusters
- **Attribute Mapping**: Complete breakdown of custom Sonoff ZCL attributes

## Documentation
📖 Full technical analysis available in the **[project Wiki](https://github.com/TapioJarnfors/Sonoff_SmartWaterValveAttributeAnalysis/wiki)** including:
- Event timelines for different flow rates
- Byte-level attribute documentation
- Packet capture samples

## Usage
```bash
# Clone repository (including wiki)
git clone --recurse-submodules https://github.com/TapioJarnfors/Sonoff_SmartWaterValveAttributeAnalysis.git
