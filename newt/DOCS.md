# Home Assistant Add-on: Newt

[Newt](https://github.com/fosrl/newt) is a fully user-space WireGuard
tunnel client and TCP/UDP proxy, designed to securely expose private resources
controlled by Pangolin. By using Newt, you don't need to manage complex
WireGuard tunnels and NATing.

Installing this add-on on your Home Assistant instance enables you to
connect your Home Assistant and other local resources to Pangolin.

## Installation

To install this Add-On, manually add the HA-Addons repository to Home Assistant
using [this GitHub repository][ha-addons] or by clicking the button below.

[![Add Repository to HA][my-ha-badge]][my-ha-url]

## Configuration

**Note**: _Remember to restart the add-on when the configuration is changed._

You need to create a new site in your Pangolin instance first. Copy the
displayed values to the respective configuration options listed below.

### Option: `pangolin_endpoint`

Set this option to the endpoint URL displayed after creating your
Pangolin site.

### Option: `newt_id`

Set this option to the id displayed after creating your
Pangolin site.

### Option: `newt_secret`

Set this option to the secret displayed after creating your
Pangolin site.

### Option: `log_level`

The `log_level` option controls the level of log output by the addon and can
be changed to be more or less verbose, which might be useful when you are
dealing with an unknown issue. Possible values are:

- `trace`: Show every detail, like all called internal functions.
- `debug`: Shows detailed debug information.
- `info`: Normal (usually) interesting events.
- `warning`: Exceptional occurrences that are not errors.
- `error`: Runtime errors that do not require immediate action.
- `fatal`: Something went terribly wrong. Add-on becomes unusable.

Please note that each level automatically includes log messages from a
more severe level, e.g., `debug` also shows `info` messages. By default,
the `log_level` is set to `info`, which is the recommended setting unless
you are troubleshooting.

[my-ha-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[my-ha-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fhomeassistant-apps%2Frepository
[ha-addons]: https://github.com/homeassistant-apps/repository
