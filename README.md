# Home Assistant Community Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![Discord][discord-shield]][discord]
[![Community Forum][forum-shield]][forum]

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

The primary goal of this project is to provide you (as a Home Assistant user)
with additional, high quality, add-ons that allow you to take your automated
home to the next level.

## Installation

In general, there is no need to install this repository on your
Home Assistant instance. It is activated and added by Home Assistant
by default.

However, if the repository is missing on your setup, adding this add-ons
repository to your Home Assistant instance is pretty easy. In the
Home Assistant add-on store, a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/hassio-addons/repository
```

## Add-ons provided by this repository


### &#10003; [Z-Wave JS UI][addon-zwave-js-ui]

![Latest Version][zwave-js-ui-version-shield]
![Supports armhf Architecture][zwave-js-ui-armhf-shield]
![Supports armv7 Architecture][zwave-js-ui-armv7-shield]
![Supports aarch64 Architecture][zwave-js-ui-aarch64-shield]
![Supports amd64 Architecture][zwave-js-ui-amd64-shield]
![Supports i386 Architecture][zwave-js-ui-i386-shield]

Fully configurable Z-Wave JS gateway and control panel

[:books: Z-Wave JS UI add-on documentation][addon-doc-zwave-js-ui]


## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

You have several options to get them answered:

- The Home Assistant Community Add-ons [Discord Chat Server][discord]
- The Home Assistant [Community Forum][forum].
- The Home Assistant [Discord Chat Server][discord-ha].
- Join the [Reddit subreddit][reddit] in [/r/homeassistant][reddit]

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Z-Wave JS UI][zwave-js-ui-issue]


For a general repository issue or add-on ideas [open an issue here][issue]

## Adding a new add-on

We are currently not accepting third party add-ons to this repository.

For questions, please contact [Franck Nijhof][frenck]:

- Drop him an email: frenck@addons.community
- Chat with him on [Discord Chat][discord]
- Message him via the forums: [frenck][forum-frenck]

## License

MIT License

Copyright (c) 2017-2024 Franck Nijhof

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-adguard]: https://github.com/hassio-addons/addon-adguard-home/tree/v5.2.5
[addon-doc-adguard]: https://github.com/hassio-addons/addon-adguard-home/blob/v5.2.5/README.md
[adguard-issue]: https://github.com/hassio-addons/addon-adguard-home/issues
[adguard-version-shield]: https://img.shields.io/badge/version-v5.2.5-blue.svg
[adguard-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[adguard-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[adguard-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[adguard-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[adguard-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-ssh]: https://github.com/hassio-addons/addon-ssh/tree/v20.0.2
[addon-doc-ssh]: https://github.com/hassio-addons/addon-ssh/blob/v20.0.2/README.md
[ssh-issue]: https://github.com/hassio-addons/addon-ssh/issues
[ssh-version-shield]: https://img.shields.io/badge/version-v20.0.2-blue.svg
[ssh-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[ssh-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ssh-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[ssh-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[ssh-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-aircast]: https://github.com/hassio-addons/addon-aircast/tree/v4.2.4
[addon-doc-aircast]: https://github.com/hassio-addons/addon-aircast/blob/v4.2.4/README.md
[aircast-issue]: https://github.com/hassio-addons/addon-aircast/issues
[aircast-version-shield]: https://img.shields.io/badge/version-v4.2.4-blue.svg
[aircast-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[aircast-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[aircast-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[aircast-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[aircast-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-airsonos]: https://github.com/hassio-addons/addon-airsonos/tree/v4.2.4
[addon-doc-airsonos]: https://github.com/hassio-addons/addon-airsonos/blob/v4.2.4/README.md
[airsonos-issue]: https://github.com/hassio-addons/addon-airsonos/issues
[airsonos-version-shield]: https://img.shields.io/badge/version-v4.2.4-blue.svg
[airsonos-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[airsonos-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[airsonos-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[airsonos-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[airsonos-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-appdaemon]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.16.7
[addon-doc-appdaemon]: https://github.com/hassio-addons/addon-appdaemon/blob/v0.16.7/README.md
[appdaemon-issue]: https://github.com/hassio-addons/addon-appdaemon/issues
[appdaemon-version-shield]: https://img.shields.io/badge/version-v0.16.7-blue.svg
[appdaemon-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[appdaemon-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[appdaemon-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[appdaemon-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[appdaemon-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-bazarr]: https://github.com/hassio-addons/addon-bazarr/tree/v0.4.1
[addon-doc-bazarr]: https://github.com/hassio-addons/addon-bazarr/blob/v0.4.1/README.md
[bazarr-issue]: https://github.com/hassio-addons/addon-bazarr/issues
[bazarr-version-shield]: https://img.shields.io/badge/version-v0.4.1-blue.svg
[bazarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[bazarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[bazarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[bazarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[bazarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-bookstack]: https://github.com/hassio-addons/addon-bookstack/tree/v2.4.2
[addon-doc-bookstack]: https://github.com/hassio-addons/addon-bookstack/blob/v2.4.2/README.md
[bookstack-issue]: https://github.com/hassio-addons/addon-bookstack/issues
[bookstack-version-shield]: https://img.shields.io/badge/version-v2.4.2-blue.svg
[bookstack-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[bookstack-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[bookstack-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[bookstack-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[bookstack-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-emqx]: https://github.com/hassio-addons/addon-emqx/tree/v0.7.4
[addon-doc-emqx]: https://github.com/hassio-addons/addon-emqx/blob/v0.7.4/README.md
[emqx-issue]: https://github.com/hassio-addons/addon-emqx/issues
[emqx-version-shield]: https://img.shields.io/badge/version-v0.7.4-blue.svg
[emqx-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[emqx-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[emqx-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[emqx-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[emqx-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-example]: https://github.com/hassio-addons/addon-example/tree/v10.1.0
[addon-doc-example]: https://github.com/hassio-addons/addon-example/blob/v10.1.0/README.md
[example-issue]: https://github.com/hassio-addons/addon-example/issues
[example-version-shield]: https://img.shields.io/badge/version-v10.1.0-blue.svg
[example-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[example-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[example-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[example-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[example-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-ftp]: https://github.com/hassio-addons/addon-ftp/tree/v5.2.1
[addon-doc-ftp]: https://github.com/hassio-addons/addon-ftp/blob/v5.2.1/README.md
[ftp-issue]: https://github.com/hassio-addons/addon-ftp/issues
[ftp-version-shield]: https://img.shields.io/badge/version-v5.2.1-blue.svg
[ftp-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[ftp-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[ftp-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[ftp-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[ftp-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-foldingathome]: https://github.com/hassio-addons/addon-foldingathome/tree/v0.7.2
[addon-doc-foldingathome]: https://github.com/hassio-addons/addon-foldingathome/blob/v0.7.2/README.md
[foldingathome-issue]: https://github.com/hassio-addons/addon-foldingathome/issues
[foldingathome-version-shield]: https://img.shields.io/badge/version-v0.7.2-blue.svg
[foldingathome-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[foldingathome-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[foldingathome-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[foldingathome-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[foldingathome-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-glances]: https://github.com/hassio-addons/addon-glances/tree/v0.21.1
[addon-doc-glances]: https://github.com/hassio-addons/addon-glances/blob/v0.21.1/README.md
[glances-issue]: https://github.com/hassio-addons/addon-glances/issues
[glances-version-shield]: https://img.shields.io/badge/version-v0.21.1-blue.svg
[glances-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[glances-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[glances-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[glances-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[glances-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-grafana]: https://github.com/hassio-addons/addon-grafana/tree/v10.4.2
[addon-doc-grafana]: https://github.com/hassio-addons/addon-grafana/blob/v10.4.2/README.md
[grafana-issue]: https://github.com/hassio-addons/addon-grafana/issues
[grafana-version-shield]: https://img.shields.io/badge/version-v10.4.2-blue.svg
[grafana-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grafana-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grafana-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[grafana-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[grafana-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-grocy]: https://github.com/hassio-addons/addon-grocy/tree/v0.24.0
[addon-doc-grocy]: https://github.com/hassio-addons/addon-grocy/blob/v0.24.0/README.md
[grocy-issue]: https://github.com/hassio-addons/addon-grocy/issues
[grocy-version-shield]: https://img.shields.io/badge/version-v0.24.0-blue.svg
[grocy-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[grocy-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[grocy-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[grocy-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[grocy-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-influxdb]: https://github.com/hassio-addons/addon-influxdb/tree/v5.0.2
[addon-doc-influxdb]: https://github.com/hassio-addons/addon-influxdb/blob/v5.0.2/README.md
[influxdb-issue]: https://github.com/hassio-addons/addon-influxdb/issues
[influxdb-version-shield]: https://img.shields.io/badge/version-v5.0.2-blue.svg
[influxdb-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[influxdb-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[influxdb-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[influxdb-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[influxdb-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-jupyterlab]: https://github.com/hassio-addons/addon-jupyterlab/tree/v0.15.9
[addon-doc-jupyterlab]: https://github.com/hassio-addons/addon-jupyterlab/blob/v0.15.9/README.md
[jupyterlab-issue]: https://github.com/hassio-addons/addon-jupyterlab/issues
[jupyterlab-version-shield]: https://img.shields.io/badge/version-v0.15.9-blue.svg
[jupyterlab-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[jupyterlab-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[jupyterlab-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[jupyterlab-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[jupyterlab-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-lidarr]: https://github.com/hassio-addons/addon-lidarr/tree/v0.8.1
[addon-doc-lidarr]: https://github.com/hassio-addons/addon-lidarr/blob/v0.8.1/README.md
[lidarr-issue]: https://github.com/hassio-addons/addon-lidarr/issues
[lidarr-version-shield]: https://img.shields.io/badge/version-v0.8.1-blue.svg
[lidarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[lidarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[lidarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[lidarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[lidarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-log-viewer]: https://github.com/hassio-addons/addon-log-viewer/tree/v0.17.1
[addon-doc-log-viewer]: https://github.com/hassio-addons/addon-log-viewer/blob/v0.17.1/README.md
[log-viewer-issue]: https://github.com/hassio-addons/addon-log-viewer/issues
[log-viewer-version-shield]: https://img.shields.io/badge/version-v0.17.1-blue.svg
[log-viewer-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[log-viewer-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[log-viewer-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[log-viewer-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[log-viewer-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-mqtt-io]: https://github.com/hassio-addons/addon-mqtt-io/tree/v0.4.0
[addon-doc-mqtt-io]: https://github.com/hassio-addons/addon-mqtt-io/blob/v0.4.0/README.md
[mqtt-io-issue]: https://github.com/hassio-addons/addon-mqtt-io/issues
[mqtt-io-version-shield]: https://img.shields.io/badge/version-v0.4.0-blue.svg
[mqtt-io-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[mqtt-io-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[mqtt-io-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[mqtt-io-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[mqtt-io-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-nut]: https://github.com/hassio-addons/addon-nut/tree/v0.14.1
[addon-doc-nut]: https://github.com/hassio-addons/addon-nut/blob/v0.14.1/README.md
[nut-issue]: https://github.com/hassio-addons/addon-nut/issues
[nut-version-shield]: https://img.shields.io/badge/version-v0.14.1-blue.svg
[nut-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nut-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nut-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nut-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[nut-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-nginxproxymanager]: https://github.com/hassio-addons/addon-nginx-proxy-manager/tree/v1.0.1
[addon-doc-nginxproxymanager]: https://github.com/hassio-addons/addon-nginx-proxy-manager/blob/v1.0.1/README.md
[nginxproxymanager-issue]: https://github.com/hassio-addons/addon-nginx-proxy-manager/issues
[nginxproxymanager-version-shield]: https://img.shields.io/badge/version-v1.0.1-blue.svg
[nginxproxymanager-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[nginxproxymanager-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[nginxproxymanager-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[nginxproxymanager-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[nginxproxymanager-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-node-red]: https://github.com/hassio-addons/addon-node-red/tree/v19.0.2
[addon-doc-node-red]: https://github.com/hassio-addons/addon-node-red/blob/v19.0.2/README.md
[node-red-issue]: https://github.com/hassio-addons/addon-node-red/issues
[node-red-version-shield]: https://img.shields.io/badge/version-v19.0.2-blue.svg
[node-red-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[node-red-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[node-red-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[node-red-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[node-red-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-overseerr]: https://github.com/hassio-addons/addon-overseerr/tree/v0.1.0
[addon-doc-overseerr]: https://github.com/hassio-addons/addon-overseerr/blob/v0.1.0/README.md
[overseerr-issue]: https://github.com/hassio-addons/addon-overseerr/issues
[overseerr-version-shield]: https://img.shields.io/badge/version-v0.1.0-blue.svg
[overseerr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[overseerr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[overseerr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[overseerr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[overseerr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-plex]: https://github.com/hassio-addons/addon-plex/tree/v3.6.3
[addon-doc-plex]: https://github.com/hassio-addons/addon-plex/blob/v3.6.3/README.md
[plex-issue]: https://github.com/hassio-addons/addon-plex/issues
[plex-version-shield]: https://img.shields.io/badge/version-v3.6.3-blue.svg
[plex-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[plex-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[plex-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[plex-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[plex-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-prowlarr]: https://github.com/hassio-addons/addon-prowlarr/tree/v0.18.0
[addon-doc-prowlarr]: https://github.com/hassio-addons/addon-prowlarr/blob/v0.18.0/README.md
[prowlarr-issue]: https://github.com/hassio-addons/addon-prowlarr/issues
[prowlarr-version-shield]: https://img.shields.io/badge/version-v0.18.0-blue.svg
[prowlarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[prowlarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[prowlarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[prowlarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[prowlarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-radarr]: https://github.com/hassio-addons/addon-radarr/tree/v0.17.0
[addon-doc-radarr]: https://github.com/hassio-addons/addon-radarr/blob/v0.17.0/README.md
[radarr-issue]: https://github.com/hassio-addons/addon-radarr/issues
[radarr-version-shield]: https://img.shields.io/badge/version-v0.17.0-blue.svg
[radarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[radarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[radarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[radarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[radarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-readarr]: https://github.com/hassio-addons/addon-readarr/tree/v0.3.1
[addon-doc-readarr]: https://github.com/hassio-addons/addon-readarr/blob/v0.3.1/README.md
[readarr-issue]: https://github.com/hassio-addons/addon-readarr/issues
[readarr-version-shield]: https://img.shields.io/badge/version-v0.3.1-blue.svg
[readarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[readarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[readarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[readarr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[readarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-sabnzbd]: https://github.com/hassio-addons/addon-sabnzbd/tree/v0.3.3
[addon-doc-sabnzbd]: https://github.com/hassio-addons/addon-sabnzbd/blob/v0.3.3/README.md
[sabnzbd-issue]: https://github.com/hassio-addons/addon-sabnzbd/issues
[sabnzbd-version-shield]: https://img.shields.io/badge/version-v0.3.3-blue.svg
[sabnzbd-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[sabnzbd-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[sabnzbd-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[sabnzbd-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[sabnzbd-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-sqlite-web]: https://github.com/hassio-addons/addon-sqlite-web/tree/v4.3.1
[addon-doc-sqlite-web]: https://github.com/hassio-addons/addon-sqlite-web/blob/v4.3.1/README.md
[sqlite-web-issue]: https://github.com/hassio-addons/addon-sqlite-web/issues
[sqlite-web-version-shield]: https://img.shields.io/badge/version-v4.3.1-blue.svg
[sqlite-web-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[sqlite-web-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[sqlite-web-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[sqlite-web-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[sqlite-web-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-sonarr]: https://github.com/hassio-addons/addon-sonarr/tree/v0.3.2
[addon-doc-sonarr]: https://github.com/hassio-addons/addon-sonarr/blob/v0.3.2/README.md
[sonarr-issue]: https://github.com/hassio-addons/addon-sonarr/issues
[sonarr-version-shield]: https://img.shields.io/badge/version-v0.3.2-blue.svg
[sonarr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[sonarr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[sonarr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[sonarr-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[sonarr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-spotify]: https://github.com/hassio-addons/addon-spotify-connect/tree/v0.14.0
[addon-doc-spotify]: https://github.com/hassio-addons/addon-spotify-connect/blob/v0.14.0/README.md
[spotify-issue]: https://github.com/hassio-addons/addon-spotify-connect/issues
[spotify-version-shield]: https://img.shields.io/badge/version-v0.14.0-blue.svg
[spotify-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[spotify-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[spotify-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[spotify-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[spotify-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-vscode]: https://github.com/hassio-addons/addon-vscode/tree/v5.18.3
[addon-doc-vscode]: https://github.com/hassio-addons/addon-vscode/blob/v5.18.3/README.md
[vscode-issue]: https://github.com/hassio-addons/addon-vscode/issues
[vscode-version-shield]: https://img.shields.io/badge/version-v5.18.3-blue.svg
[vscode-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[vscode-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[vscode-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[vscode-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[vscode-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-tailscale]: https://github.com/hassio-addons/addon-tailscale/tree/v0.25.0
[addon-doc-tailscale]: https://github.com/hassio-addons/addon-tailscale/blob/v0.25.0/README.md
[tailscale-issue]: https://github.com/hassio-addons/addon-tailscale/issues
[tailscale-version-shield]: https://img.shields.io/badge/version-v0.25.0-blue.svg
[tailscale-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tailscale-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tailscale-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tailscale-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tailscale-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-tasmoadmin]: https://github.com/hassio-addons/addon-tasmoadmin/tree/v0.31.4
[addon-doc-tasmoadmin]: https://github.com/hassio-addons/addon-tasmoadmin/blob/v0.31.4/README.md
[tasmoadmin-issue]: https://github.com/hassio-addons/addon-tasmoadmin/issues
[tasmoadmin-version-shield]: https://img.shields.io/badge/version-v0.31.4-blue.svg
[tasmoadmin-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tasmoadmin-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tasmoadmin-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tasmoadmin-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tasmoadmin-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-tautulli]: https://github.com/hassio-addons/addon-tautulli/tree/v4.2.1
[addon-doc-tautulli]: https://github.com/hassio-addons/addon-tautulli/blob/v4.2.1/README.md
[tautulli-issue]: https://github.com/hassio-addons/addon-tautulli/issues
[tautulli-version-shield]: https://img.shields.io/badge/version-v4.2.1-blue.svg
[tautulli-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tautulli-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tautulli-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tautulli-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tautulli-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-thelounge]: https://github.com/hassio-addons/addon-thelounge/tree/v0.20.0
[addon-doc-thelounge]: https://github.com/hassio-addons/addon-thelounge/blob/v0.20.0/README.md
[thelounge-issue]: https://github.com/hassio-addons/addon-thelounge/issues
[thelounge-version-shield]: https://img.shields.io/badge/version-v0.20.0-blue.svg
[thelounge-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[thelounge-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[thelounge-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[thelounge-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[thelounge-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-tor]: https://github.com/hassio-addons/addon-tor/tree/v6.0.0
[addon-doc-tor]: https://github.com/hassio-addons/addon-tor/blob/v6.0.0/README.md
[tor-issue]: https://github.com/hassio-addons/addon-tor/issues
[tor-version-shield]: https://img.shields.io/badge/version-v6.0.0-blue.svg
[tor-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[tor-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[tor-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[tor-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[tor-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-traccar]: https://github.com/hassio-addons/addon-traccar/tree/v0.25.0
[addon-doc-traccar]: https://github.com/hassio-addons/addon-traccar/blob/v0.25.0/README.md
[traccar-issue]: https://github.com/hassio-addons/addon-traccar/issues
[traccar-version-shield]: https://img.shields.io/badge/version-v0.25.0-blue.svg
[traccar-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[traccar-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[traccar-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[traccar-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[traccar-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-unifi]: https://github.com/hassio-addons/addon-unifi/tree/v4.0.2
[addon-doc-unifi]: https://github.com/hassio-addons/addon-unifi/blob/v4.0.2/README.md
[unifi-issue]: https://github.com/hassio-addons/addon-unifi/issues
[unifi-version-shield]: https://img.shields.io/badge/version-v4.0.2-blue.svg
[unifi-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[unifi-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[unifi-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[unifi-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[unifi-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-uptime-kuma]: https://github.com/hassio-addons/addon-uptime-kuma/tree/v0.13.0
[addon-doc-uptime-kuma]: https://github.com/hassio-addons/addon-uptime-kuma/blob/v0.13.0/README.md
[uptime-kuma-issue]: https://github.com/hassio-addons/addon-uptime-kuma/issues
[uptime-kuma-version-shield]: https://img.shields.io/badge/version-v0.13.0-blue.svg
[uptime-kuma-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[uptime-kuma-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[uptime-kuma-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[uptime-kuma-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[uptime-kuma-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-bitwarden]: https://github.com/hassio-addons/addon-bitwarden/tree/v0.24.1
[addon-doc-bitwarden]: https://github.com/hassio-addons/addon-bitwarden/blob/v0.24.1/README.md
[bitwarden-issue]: https://github.com/hassio-addons/addon-bitwarden/issues
[bitwarden-version-shield]: https://img.shields.io/badge/version-v0.24.1-blue.svg
[bitwarden-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[bitwarden-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[bitwarden-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[bitwarden-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[bitwarden-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-whisparr]: https://github.com/hassio-addons/addon-whisparr/tree/v0.3.1
[addon-doc-whisparr]: https://github.com/hassio-addons/addon-whisparr/blob/v0.3.1/README.md
[whisparr-issue]: https://github.com/hassio-addons/addon-whisparr/issues
[whisparr-version-shield]: https://img.shields.io/badge/version-v0.3.1-blue.svg
[whisparr-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[whisparr-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[whisparr-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[whisparr-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[whisparr-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-wireguard]: https://github.com/hassio-addons/addon-wireguard/tree/v0.11.0
[addon-doc-wireguard]: https://github.com/hassio-addons/addon-wireguard/blob/v0.11.0/README.md
[wireguard-issue]: https://github.com/hassio-addons/addon-wireguard/issues
[wireguard-version-shield]: https://img.shields.io/badge/version-v0.11.0-blue.svg
[wireguard-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[wireguard-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[wireguard-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[wireguard-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[wireguard-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-zwave-js-ui]: https://github.com/hassio-addons/addon-zwave-js-ui/tree/v3.23.0
[addon-doc-zwave-js-ui]: https://github.com/hassio-addons/addon-zwave-js-ui/blob/v3.23.0/README.md
[zwave-js-ui-issue]: https://github.com/hassio-addons/addon-zwave-js-ui/issues
[zwave-js-ui-version-shield]: https://img.shields.io/badge/version-v3.23.0-blue.svg
[zwave-js-ui-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[zwave-js-ui-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[zwave-js-ui-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[zwave-js-ui-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[zwave-js-ui-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-zerotier]: https://github.com/hassio-addons/addon-zerotier/tree/v0.20.0
[addon-doc-zerotier]: https://github.com/hassio-addons/addon-zerotier/blob/v0.20.0/README.md
[zerotier-issue]: https://github.com/hassio-addons/addon-zerotier/issues
[zerotier-version-shield]: https://img.shields.io/badge/version-v0.20.0-blue.svg
[zerotier-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[zerotier-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[zerotier-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[zerotier-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[zerotier-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-chrony]: https://github.com/hassio-addons/addon-chrony/tree/v5.1.0
[addon-doc-chrony]: https://github.com/hassio-addons/addon-chrony/blob/v5.1.0/README.md
[chrony-issue]: https://github.com/hassio-addons/addon-chrony/issues
[chrony-version-shield]: https://img.shields.io/badge/version-v5.1.0-blue.svg
[chrony-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[chrony-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[chrony-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[chrony-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[chrony-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-motioneye]: https://github.com/hassio-addons/addon-motioneye/tree/v0.21.0
[addon-doc-motioneye]: https://github.com/hassio-addons/addon-motioneye/blob/v0.21.0/README.md
[motioneye-issue]: https://github.com/hassio-addons/addon-motioneye/issues
[motioneye-version-shield]: https://img.shields.io/badge/version-v0.21.0-blue.svg
[motioneye-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[motioneye-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[motioneye-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[motioneye-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[motioneye-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[addon-phpmyadmin]: https://github.com/hassio-addons/addon-phpmyadmin/tree/v0.11.1
[addon-doc-phpmyadmin]: https://github.com/hassio-addons/addon-phpmyadmin/blob/v0.11.1/README.md
[phpmyadmin-issue]: https://github.com/hassio-addons/addon-phpmyadmin/issues
[phpmyadmin-version-shield]: https://img.shields.io/badge/version-v0.11.1-blue.svg
[phpmyadmin-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[phpmyadmin-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[phpmyadmin-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[phpmyadmin-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[phpmyadmin-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[awesome-shield]: https://img.shields.io/badge/awesome%3F-yes-brightgreen.svg
[awesome]: https://awesome-ha.com
[discord-ha]: https://discord.gg/c5DvZ4e
[discord-shield]: https://img.shields.io/discord/478094546522079232.svg
[discord]: https://discord.me/hassioaddons
[forum-frenck]: https://community.home-assistant.io/u/frenck/?u=frenck
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[forum]: https://community.home-assistant.io?u=frenck
[frenck]: https://github.com/frenck
[gitlabci-shield]: https://gitlab.com/hassio-addons/repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/hassio-addons/repository/pipelines
[issue]: https://github.com/hassio-addons/repository/issues
[license-shield]: https://img.shields.io/github/license/hassio-addons/repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2024.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html