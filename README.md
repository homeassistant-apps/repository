# Unofficial Home Assistant Apps (Add-ons) Repository

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

## About

Home Assistant allows anyone to create add-on repositories to share their
add-ons for Home Assistant easily. This repository is one of those repositories,
providing extra Home Assistant add-ons for your installation.

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/homeassistant-apps/repository
```

## Add-ons provided by this repository

### &#10003; [Advanced Code Server][addon-code-server]

![Latest Version][code-server-version-shield]
![Supports armhf Architecture][code-server-armhf-shield]
![Supports armv7 Architecture][code-server-armv7-shield]
![Supports aarch64 Architecture][code-server-aarch64-shield]
![Supports amd64 Architecture][code-server-amd64-shield]
![Supports i386 Architecture][code-server-i386-shield]

Code Server experience integrated in the Home Assistant frontend.

[:books: Advanced Code Server add-on documentation][addon-doc-code-server]

### &#10003; [Cloudflared][addon-cloudflared]

![Latest Version][cloudflared-version-shield]
![Supports armhf Architecture][cloudflared-armhf-shield]
![Supports armv7 Architecture][cloudflared-armv7-shield]
![Supports aarch64 Architecture][cloudflared-aarch64-shield]
![Supports amd64 Architecture][cloudflared-amd64-shield]
![Supports i386 Architecture][cloudflared-i386-shield]

Use a Cloudflare Tunnel to remotely connect to Home Assistant without opening any ports

[:books: Cloudflared add-on documentation][addon-doc-cloudflared]

### &#10003; [Newt][addon-newt]

![Latest Version][newt-version-shield]
![Supports armhf Architecture][newt-armhf-shield]
![Supports armv7 Architecture][newt-armv7-shield]
![Supports aarch64 Architecture][newt-aarch64-shield]
![Supports amd64 Architecture][newt-amd64-shield]
![Supports i386 Architecture][newt-i386-shield]

Tunneling client to connect Home Assistant to Pangolin.

[:books: Newt add-on documentation][addon-doc-newt]

## Releases

Releases are based on [Semantic Versioning][semver], and use the format
of ``MAJOR.MINOR.PATCH``. In a nutshell, the version will be incremented
based on the following:

- ``MAJOR``: Incompatible or major changes.
- ``MINOR``: Backwards-compatible new features and enhancements.
- ``PATCH``: Backwards-compatible bugfixes and package updates.

## Support

Got questions?

Open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: Advanced Code Server][code-server-issue]
- [Open an issue for the add-on: Cloudflared][cloudflared-issue]
- [Open an issue for the add-on: Newt][newt-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2025 [homeassistant-apps][github-org]

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

[addon-code-server]: https://github.com/homeassistant-apps/app-code-server/tree/v4.2.3
[addon-doc-code-server]: https://github.com/homeassistant-apps/app-code-server/blob/v4.2.3/README.md
[code-server-issue]: https://github.com/homeassistant-apps/app-code-server/issues
[code-server-version-shield]: https://img.shields.io/badge/version-v4.2.3-blue.svg
[code-server-aarch64-shield]: https://img.shields.io/badge/aarch64-no-red.svg
[code-server-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[code-server-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[code-server-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[code-server-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-cloudflared]: https://github.com/homeassistant-apps/app-cloudflared/tree/v7.0.1
[addon-doc-cloudflared]: https://github.com/homeassistant-apps/app-cloudflared/blob/v7.0.1/README.md
[cloudflared-issue]: https://github.com/homeassistant-apps/app-cloudflared/issues
[cloudflared-version-shield]: https://img.shields.io/badge/version-v7.0.1-blue.svg
[cloudflared-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[cloudflared-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[cloudflared-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[cloudflared-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[cloudflared-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[addon-newt]: https://github.com/homeassistant-apps/app-newt/tree/v1.0.0
[addon-doc-newt]: https://github.com/homeassistant-apps/app-newt/blob/v1.0.0/README.md
[newt-issue]: https://github.com/homeassistant-apps/app-newt/issues
[newt-version-shield]: https://img.shields.io/badge/version-v1.0.0-blue.svg
[newt-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[newt-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[newt-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[newt-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[newt-i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[gitlabci-shield]: https://gitlab.com/homeassistant-apps/repository/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/homeassistant-apps/repository/pipelines
[issue]: https://github.com/homeassistant-apps/repository/issues
[license-shield]: https://img.shields.io/github/license/homeassistant-apps/repository.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[semver]: http://semver.org/spec/v2.0.0.html
[github-org]: https://github.com/homeassistant-apps