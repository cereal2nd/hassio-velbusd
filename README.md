# Home Assistant VelbusD addon

This addon basically implements [Velbus TCP](https://github.com/velbus/python-velbustcp) as a home-assistant addon.

![Project Stage][project-stage-shield]
![Project Maintenance][maintenance-shield]

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![Add Repository to HA][my-ha-badge]][my-ha-url]

> This project requires financial support, but it is free for you to use. You can join those helping to keep the lights on at:
>
> [<img src="images/bmc-button.svg" width=150 height=40 style="margin: 5px"/>](https://buymeacoffee.com/cereal2nd) >[<img src="images/github-sponsors-button.svg" width=150 height=40 style="margin: 5px"/>](https://github.com/sponsors/cereal2nd/)

## Installation

1. Navigate in your Home Assistant frontend to <kbd>Settings</kbd> -> <kbd>Add-ons</kbd> -> <kbd>Add-on Store (Bottom Right)</kbd>.
2. Click the 3-dots menu at upper right <kbd>...</kbd> > <kbd>Repositories</kbd> and add this repository's URL: [https://github.com/cereal2nd/hassio-velbusd/](https://github.com/cereal2nd/hassio-velbusd/)
3. Reload the page , scroll to the bottom to find the new repository, and click the new add-on named "Home Assistant Google Drive Backup":
   Note: Home Assistant loads the repository in the background and the new item won't always show up automatically. You might need to wait a few seconds and then "hard refesh" the page for it to show up. On most browser the keyboard shortcut for this is CTRL+F5. If it still doesn't show up, clear your browser's cache and it should then.
4. Click <kbd>Install</kbd> and give it a few minutes to finish downloading.
5. Click on <kbd>Configuration</kbd> in the top menu
6. Select the device that mentions <kbd>Velleman</kbd>.
7. Click <kbd>Start</kbd>, give it a few seconds to spin up.
8. Look at the <kbd>Logs</kbd> page to see if the system is starting corectly

## Support

Got questions?

Feel free to [open an issue here][issue] on GitHub.

[my-ha-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[my-ha-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https://github.com/cereal2nd/hassio-velbusd
[ha-addons]: https://github.com/cereal2nd/hassio-velbusd
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[issue]: https://github.com/cereal2nd/hassio-velbusd/issues
