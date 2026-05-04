# Renovate Configuration Presets

This repository hosts my personal Renovate configuration
[presets](https://docs.renovatebot.com/key-concepts/presets/), designed to be
reused and extended across my other repositories that use Renovate for
dependency management.

## Disclaimer

These presets are tailored to my own workflows and preferences and are not
intended for general use by directly including them in your own repositories.
You are welcome to use them as a reference or inspiration.

## Usage

To include the default preset, `default.json`, of this repository in another
repository, reference it in the `extends` array of the Renovate configuration
file (e.g. `renovate.json`) with `"github>on2e/renovate-config"`.

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": ["github>on2e/renovate-config"]
}
```
