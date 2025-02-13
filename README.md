# Uhome (U-Tec) Home Assistant Integration

[![GitHub Release][releases-shield]][releases]
[![GitHub Activity][commits-shield]][commits]
[![License][license-shield]](LICENSE)

[![pre-commit][pre-commit-shield]][pre-commit]
[![Black][black-shield]][black]

[![hacs][hacsbadge]][hacs]

**Platform Support.**

| Platform        | Description                                                               |
| --------------- | ------------------------------------------------------------------------- |
| `Lock`          | Supports ultraloq smart locks (all types, dependent on wifi connection).  |
| `Door Sensor`   | Supports companion door sensors.                                          |
| `switch`        | Support for U-tec switches.                                               |
| `Light`         | Waiting for U-tec to implement API capabilities for Lights.               |


### HACS (Recommended)
1. Open HACS in your Home Assistant instance\
2. Click on "Integrations"\
3. Add this repo as a custom component\
4. Click "Install"\
5. Restart Home Assistant

### Manual Installation
1. Download the repository\
2. Copy the custom_components/u_tec folder to your Home Assistant's custom_components directory\
3. Restart Home Assistant

## Getting Your Credentials
Visit the U-tec developer portal\
[Apply for developer credentials](https://developer.uhomelabs.com/hc/en-us/requests/new) (They allow end-user, as a reason)\
Note down your:
- Client ID
- Client Secret

In the Uhome app, under the developer tab -  
    Set redirect URI - `https://my.home-assistant.io/redirect/oauth`

## Configuration
In Home Assistant, go to Configuration > Integrations\
Click the "+" button to add a new integration\
Search for "u-tec"\
You will need to provide:
- Client ID
- Client Secret
- API Scope (default: 'openapi')

## Configuration is done in the UI

<!---->


## Troubleshooting
See [FAQ](https://github.com/LF2b2w/Uhome-HA/discussions/2)


## Contributions are welcome!
If you want to contribute to this please read the [Contribution guidelines](CONTRIBUTING.md)

## Support
If you encounter any issues or have questions: Check the [Issues](https://github.com/LF2b2w/Uhome-HA/issues) page
Create a new issue if your problem isn't already reported

[Join](https://github.com/LF2b2w/Uhome-HA/discussions) the discussion in the Home Assistant community forums

---
Made with ❤️ by @LF2b2w

[integration_blueprint]: https://github.com/custom-components/integration_blueprint
[black]: https://github.com/psf/black
[black-shield]: https://img.shields.io/badge/code%20style-black-000000.svg?style=for-the-badge
[buymecoffee]: https://www.buymeacoffee.com/oncleben31
[buymecoffeebadge]: https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg?style=for-the-badge
[commits-shield]: https://img.shields.io/github/commit-activity/y/oncleben31/cookiecutter-homeassistant-custom-component-instance.svg?style=for-the-badge
[commits]: https://github.com/LF2b2w/U-Tec-HomeAssistant/commits/main
[hacs]: https://hacs.xyz
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[discord]: https://discord.gg/Qa5fW2R
[discord-shield]: https://img.shields.io/discord/330944238910963714.svg?style=for-the-badge
[exampleimg]: example.png
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg?style=for-the-badge
[forum]: https://community.home-assistant.io/
[license-shield]: https://img.shields.io/github/license/oncleben31/cookiecutter-homeassistant-custom-component-instance.svg?style=for-the-badge
[maintenance-shield]: https://img.shields.io/badge/maintainer-%40oncleben31-blue.svg?style=for-the-badge
[pre-commit]: https://github.com/pre-commit/pre-commit
[pre-commit-shield]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?style=for-the-badge
[releases-shield]: https://img.shields.io/github/release/oncleben31/cookiecutter-homeassistant-custom-component-instance.svg?style=for-the-badge
[releases]: https://github.com/LF2b2w/U-Tec-HomeAssistant/releases
[user_profile]: https://github.com/LF2b2w
