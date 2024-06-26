# 🎧 gPodder

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![hacs][hacsbadge]][hacs]
[![License][license-shield]](LICENSE.md)

![Project Maintenance][maintenance-shield]
[![BuyMeCoffee][buymecoffeebadge]][buymecoffee]

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

_Component to integrate with [gPodder][gpodder]._

**This component will set up the following platforms.**

Platform | Description
-- | --
`sensor` | Show info from gPodder API and expose services.

## Pre-Installation
1. Setup an account at your favourite gPodder server. You can use the official gpodder.net service or use a self-hosted one.
1. Subscribe to your favorite podcasts (I hope to add subscription management from the component in the future)
1. Make sure your subscriptions are being synced to the device you intend to use in Home Assistant.

## Installation

1. Using you tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
1. If you do not have a `custom_components` directory (folder) there, you need to create it.
1. In the `custom_components` directory (folder) create a new folder called `gpodder`.
1. Download the `gpodder.zip` the file from the latest release <https://github.com/custom-components/gpodder/releases/latest>
1. Uzip the file and place the files files you downloaded in the new directory (folder) you created.
1. Configure gPodder in the UI
1. Use the [podcast-card](https://github.com/custom-cards/podcast-card) to play podcasts to your devices.


## Configuration is done in the UI

## Contributions are welcome!

If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

***

[buymecoffee]: https://www.buymeacoffee.com/iantrich
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-blue.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/custom-components/gpodder.svg?style=for-the-badge
[commits]: https://github.com/custom-components/gpodder/commits/master
[hacs]: https://github.com/hacs/integration
[hacsbadge]: https://img.shields.io/badge/hacs-true-success.svg?style=for-the-badge
[discord]: https://discord.gg/Qa5fW2R
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg?style=for-the-badge
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/t/podcast-card-component-for-gpodder/106758
[gpodder]: https://gpodder.net/
[license-shield]: https://img.shields.io/github/license/custom-components/gpodder.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-Ian%20Richardson%20%40iantrich-blue.svg?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/custom-components/gpodder.svg?style=for-the-badge
[releases]: https://github.com/custom-components/gpodder/releases
