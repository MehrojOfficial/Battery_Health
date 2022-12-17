# Safe Charging in AOSP ROMs

#### If you are using Custom/GSI ROMs there is a high risk of reducing the battery health without smart charging of MIUI. Even some ROMs have built-in integration systems it would be better to have guaranteed working method. You might lose the highest possible charging speed. It is worth it. Better safe than regret.

## Features:
- **The lowest possible battery percentage** (to prevent offline charging issues by shutting down the device earlier with enough power left)
- **The cooldown feature by reducing charging speed** (to prevent uncontrolled charging)
- **Limited charging percentage** (to prevent overcharging when you left the device charging for whole night)
- **Fully customizable time/temperature limits** (to make it support more devices)
- **Detailed information about battery** (temperature, capacity, voltage, power, income/outcome, etc ...)
- **Comfortable UI experience rather than messy terminal codes**
___

### How to use:
- Flash both modules in Magisk
- Reboot and configure some options within app

## Recommended settings:

### ACC Settings/Configuration/Capacity:
- Shutdown below -> 2% (fully draining battery is not a good idea)
- Cooldown above -> 50% (prevention of overheating)
- Charge below -> 70% (healthier charging cycle)
- Pause above -> 90% (prevention of overcharging)

### ACC Settings/Configuration/Temperature:
- Cooldown above -> 35°C (prevention of overheating)
- Pause above -> 40°C (it is dangerous to charge in this temperature)
- Shutdown above -> 45°C (it is deadly to keep the phone on in this condition)

### ACC Settings/Configuration/Cooldown cycle:
- Charge period -> 50s
- Cooldown period -> 10s

*other settings recommended not to play without required knowledge

### Download -> [Direct Link](https://www.pling.com/p/1956709)

## Credits:
- [VR-25](https://github.com/VR-25/)
- [CrazyBoyFeng](https://github.com/CrazyBoyFeng)
- [@byMEHROJ](https://t.me/byMehroj)
