# IKEA Bilresa Scroll Wheel Blueprint (Improved)

This repository contains an improved version of the Home Assistant blueprint for the IKEA Bilresa Matter scroll wheel remote.

## Improvements in This Fork
- Reliable suffix‑based entity detection  
  Works even when entities are renamed (e.g., `event.bedroom_pos_1_cw`, `event.livingroom_pos_1_press`).
- Supports multiple scroll wheels with unique naming prefixes.
- Fully compatible with relaxed and instant scroll modes.
- Supports all click types: single, double, triple, long‑press, and hold.
- Cleaner, more maintainable trigger variable logic.

## Credit
This blueprint is based on the original work by **jhol-byte**, published in the Home Assistant Community forums.
https://community.home-assistant.io/t/ikea-bilresa-scroll-wheel-blueprint-matter-the-original/965365
This fork enhances compatibility, naming flexibility, and long‑term maintainability.

## Usage
Import the blueprint into Home Assistant using the raw GitHub URL: https://raw.githubusercontent.com/bradbowles/home-assistant-bilresa-blueprint/refs/heads/main/ikea_bilresa_scroll_wheel.yaml

Entities were renamed to:
event.pos_1_cw
event.pos_1_ccw
event.pos_1_press
event.pos_2_cw
event.pos_2_ccw
event.pos_2_press
event.pos_3_cw
event.pos_3_ccw
event.pos_3_press
