# Island for Mac

Island is a macOS overlay for coding-agent activity, Spotify lyrics, and optional plugins.

This repository distributes signed application binaries and release notes. Island's core app is proprietary. The [plugin SDK](https://github.com/Sullivansome/island-plugin-sdk), [Agent Pulse](https://github.com/Sullivansome/agent-pulse), and [Spotify plugin](https://github.com/Sullivansome/spotify-lyrics) have separate open-source repositories.

## Availability

Island 1.0.0 supports Apple silicon Macs running macOS 12 or later. The app and disk image are Developer ID signed, notarized by Apple, and stapled.

**Purchases are not open yet.** Downloads are available to inspect the installer and activation screen; plugin operation requires a valid Island 1.x license. There is no free trial in this build. Do not install expecting to activate until checkout is available.

The planned license is US$19 once for two Macs, including continued use and updates within Island 1.x. Future major upgrades are optional. Applicable taxes are shown at checkout. Refund requests are accepted within 14 days, with statutory rights preserved.

[Website](https://island.brighteng.org/) · [Pricing](https://island.brighteng.org/pricing/) · [Terms](https://island.brighteng.org/terms/) · [Privacy](https://island.brighteng.org/privacy/)

Support: kevin@brighteng.org

## Install

Download the DMG from [Releases](https://github.com/Sullivansome/island-releases/releases), open it, and drag Island to Applications. Keep Gatekeeper and quarantine checks enabled.

Homebrew:

```sh
brew install --cask Sullivansome/tap/island
```

If Homebrew requests trust for this vendor tap, review [the cask](https://github.com/Sullivansome/homebrew-tap/blob/main/Casks/island.rb), run `brew trust --cask Sullivansome/tap/island`, then repeat the installation. This trusts only the Island recipe, not every item in the tap.

After purchasing, enter the license key from your Creem receipt in **Island → Settings → License**. Manage devices there when replacing a Mac. A successfully activated Mac can operate offline for up to 30 days before reconnecting.

## License

Downloading does not transfer ownership of Island's proprietary source or grant redistribution rights beyond the customer terms. Open-source dependency notices and applicable licenses are bundled with the app. GitHub's automatically generated source archives contain only this distribution repository, not the core app source.
