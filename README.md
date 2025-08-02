# Sonoff Smart Water Valve Attribute Analysis

[![Wiki Documentation](https://img.shields.io/badge/Documentation-Wiki-blue)](https://github.com/TapioJarnfors/Sonoff_SmartWaterValveAttributeAnalysis/wiki)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Overview
This project provides a detailed analysis of the event timeline for the Sonoff Smart Water Valve, focusing on both quantitative and timed irrigation cycles. The analysis is based on Zigbee packet captures, highlighting key events and their corresponding attributes.

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
