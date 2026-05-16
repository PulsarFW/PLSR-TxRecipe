<div align="center">
  <img src="https://r2.fivemanage.com/GPYOH8Hq4GPyAY7czrgLe/pulsarbanner.png" alt="Pulsar Framework" width="100%">

# Pulsar Framework

**Server installation guide for Pulsar Framework**

[![FiveM](https://img.shields.io/badge/FiveM-F40552?style=flat-square)]()
[![GitHub Release](https://img.shields.io/github/v/release/PulsarFW/PLSR-TxRecipe?style=flat-square)]()

[Overview](#overview) • [Installation](#installation) • [License](#license)
</div>

## Overview

Server configuration files and installation guide for deploying a full Pulsar Framework server. All resources are distributed via GitHub Releases.

## Installation

1. Download the latest release from the [Releases](https://github.com/PulsarFW/PLSR-TxRecipe/releases/latest) page
2. Extract all resources into your server's `resources/` folder
3. Import `pulsar.sql` into your database
4. Copy `server.cfg` and the `configs/` folder to your server root
5. Fill in the required values in `server.cfg`:
   - `sv_licenseKey` — your Cfx.re license key from [keymaster.fivem.net](https://keymaster.fivem.net)
   - `steam_webApiKey` — your Steam API key from [steamcommunity.com/dev/apikey](https://steamcommunity.com/dev/apikey)
   - Database credentials

**Notes:**
- `pulsar-ws` requires `cert.pem` and `key.pem` placed manually in `resources/[pulsar]/pulsar-ws/`

## License

Copyright © 2026 Pulsar Framework. All rights reserved.

<div align="center">

[![Pulsar Framework](https://img.shields.io/badge/Pulsar-Framework-7c3aed?style=flat-square)]()
[![Built for FiveM](https://img.shields.io/badge/Built_for-FiveM-F40552?style=flat-square)]()

</div>
