# Renovate Config

Shared Renovate Bot Config Preset

## Usage

Add the following to your `renovate.json` file:

```jsonc
{
    "extends": ["github>ryoppippi/renovate-config"],

    // or
    "extends": ["gitlab>ryoppippi/renovate-config:no-group"],

    // override any settings here
    "automerge": true
}
```
