# MajorDom Systems

**The developer ecosystem around [MajorDom](https://www.majordom.io)** — the private, offline-first smart home system by [Parker Industries](https://github.com/ParkerIndustries).

Build **on** MajorDom, or hack **on** MajorDom itself. 

- 🏠 **The product (for users):** [majordom.io](https://www.majordom.io)
- 🔌 **ESPHome for MajorDom:** [docs.majordom.io/esphome-components](https://docs.majordom.io/esphome-components/) — ESPHome external components, starting with runtime Thread provisioning over BLE
- 📖 **Build an integration:** [docs.majordom.io/integrations](https://docs.majordom.io/integrations)
- 🤝 **Licensing, partnership, collaborations:** [parker-industries.org/partnership](https://parker-industries.org/partnership)

### What's here

The open pieces of MajorDom: peripheral firmware and the toolkit for adding a device protocol.
The libraries are standalone, published to PyPI and usable on their own — not just inside the Hub.

- **[firmware](https://majordom-systems.github.io/firmware/)** — firmware for MajorDom peripherals and supported third-party devices, built in CI and published as a signed channel.
- **[integration-sdk](https://github.com/MajorDom-Systems/integration-sdk)** (`majordom-integration-sdk`) — the framework integrations build on: the controller lifecycle, device & parameter models, discovery services (mDNS / SSDP / BLE), and offline test doubles.
- **[integration-template](https://github.com/MajorDom-Systems/integration-template)** — scaffold a new integration with **Use this template**: prefilled CI, tests, and an implementation checklist.
- **Official integrations** ([browse them all](https://github.com/orgs/MajorDom-Systems/repositories?q=integration-)):
  - **[integration-esphome](https://github.com/MajorDom-Systems/integration-esphome)** (`majordom-esphome`) — ESPHome devices over the native API (`aioesphomeapi`).
  - **[integration-matter](https://github.com/MajorDom-Systems/integration-matter)** (`majordom-matter`) — Matter over Thread / Wi-Fi.
  - **[integration-zigbee](https://github.com/MajorDom-Systems/integration-zigbee)** (`majordom-zigbee`) — Zigbee via `zigpy`.
  - **[integration-zwave](https://github.com/MajorDom-Systems/integration-zwave)** (`majordom-zwave`) — Z-Wave via `zwave-js` (`zwave-js-server`).
  - **[integration-homekit](https://github.com/MajorDom-Systems/integration-homekit)** (`majordom-homekit`) — Apple HomeKit (HAP).

Adding a new protocol? Start from the template and follow the [integration docs](https://docs.majordom.io/integrations).

### Powered by
- **[STARK](https://stark.markparker.me)** ([source](https://github.com/MarkParker5/STARK)) — the powerful offline voice engine behind Archie.
- Maintained by the [Parker Industries](https://github.com/ParkerIndustries) team.
