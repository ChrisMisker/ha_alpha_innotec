# Alpha Home Assistant integration

![Version](https://img.shields.io/github/v/release/arjenbos/ha_alpha_innotec)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)

A custom Home Assistant integration for the Alpha Home intelligent room temperature system. This is not to control the Alpha Innotec heatpump (use the Luxtronik integration for that, see: https://github.com/BenPru/luxtronik), but for when you use the Alpha Home system (which uses temperature sensors and valve groups). With this integration, you can read the temperature sensors, set the desired temperature and see the state of your valves in your Alpha Home system.  
 
## Pre-install
1. Create a user for Home Assistant in the control box; it's **not recommended** to use a shared user.
2. Ensure Home Assistant is able to reach the control box via the local network.
3. Ensure Home Assistant is able to reach the gateway via the local network.
4. You need to have the password for the gateway.

## Install
1. Add this repository as a custom repository in HACS.
2. Install the integration.

## Disclaimer
- I cannot say that i'm a python developer. So, if you see code that's bad practice. Please, feel free to contribute to this integration via a pull request. 
- I do not own an Alpha Innotec heat pump. If you have an issue, please provide sample data and information about your installation because testing without sample data is impossible.
