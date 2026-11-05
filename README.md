# SolusIO

Auto-provision SolusIO from PeltyCMS orders

Official provisioning module for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Providers who sell hosting, VPS, game panels or cloud and need auto-create on payment.

## Features

- Create services on **SolusIO** when the customer pays
- Suspend, unsuspend and terminate follow the Pelty service lifecycle
- Map Pelty products to packages / plans on the remote panel
- API tokens stay in Pelty secrets

## How it works

1. Install **SolusIO** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-solusio) inside Pelty Admin → Addons.
2. Open Pelty Admin → Products, map a product to the SolusIO module, and save API credentials.
3. Customers hit checkout / login / order flow as usual — SolusIO runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working SolusIO credentials
- Outbound HTTPS from your panel

## Get it

**[SolusIO on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/provisioning-solusio)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
