# hw_advancedjewelry

## Description
Advanced Jewelry Robbery Script using ox_lib and ox_target (or qtarget) for ESX. Players can purchase necessary items, disable alarms by hacking, loot the store, and sell the items. The police will be notified during the robbery.

## Installation
1. Add the script to your resources folder.
2. Add `ensure hw_advancedjewelry` to your `server.cfg`.

## Configuration
Modify `config.lua` to change settings like locations, required items, police job, and webhook URL.

## Features
- Purchase items from ped
- Hack device to disable alarms
- Loot the store
- Notify police
- Sell items for bonus payout
- Discord webhook logs
- Debug prints for developers

## Dependencies
- ESX
- ox_lib
- ox_target or qtarget (choose one and configure in `fxmanifest.lua`)
