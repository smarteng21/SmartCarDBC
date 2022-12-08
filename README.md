CAN Matrix files for Smart cars. Currently available for Smart ForTwo 450 and Smart Roadster. More to follow...

[![License](https://img.shields.io/github/license/smarteng21/SmartCarDBC?color=orange)](LICENSE)

## What is a DBC file and what can I use it for?

The DBC files contain information needed to "translate" a vehicle's CAN bus traffic into a human readable format. This includes position and length of a certain piece of information inside a CAN frame as well as offsets and multipliers used to transform the binary value into a physical value (ie. rpm, speed, temperature).

## Usage

To create or edit a DBC file you can use any software that correctly reads this format such as SavvyCan, Vector CANdb++, etc.

If you find this repo useful, give it a star, or fork it and contribute!

[![GitHub stars](https://img.shields.io/github/stars/smarteng21/Smartcardbc?style=social&label=Star)](https://github.com/smarteng21/Smartcardbc/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/smarteng21/smartcardbc?style=social&label=Fork)](https://github.com/smarteng21/Smartcardbc/network)

## Development

The reverse engineering of the Smart ForTwo / Roadster CAN bus began as part of a bigger project: Full LCD Instrument Cluster. The project will be open sourced when it's ready.

## Contribute

You can contribute by
- Providing Pull Requests (fixes, decoding missing messages / signals)
- Testing existing signals and report issues
- Start working on the Smart ForTwo 451 CAN bus
- Donating to keep the project alive 

[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://paypal.me/smarteng21)

## Disclaimer

We don't take any responsibility nor liability for using the content provided in this repository.

## License

This program is licensed under MIT
