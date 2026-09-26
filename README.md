# Better Player for Twitch

Better Player for Twitch enhances Twitch's native player in Firefox with additional playback, audio, and quality-of-life controls.

This repository is the public home for **documentation, support, bug reports, and feature requests** for Better Player for Twitch.

> Better Player for Twitch is an independent project and is not affiliated with or endorsed by Twitch Interactive, Inc.

## Features

- Uses Twitch's native web player
- Cleaner playback during Twitch video ad breaks when available
- Global audio compressor with Soft, Balanced, Strong, and Max presets
- Per-channel compressor overrides
- Per-channel five-band equalizer profiles
- Video brightness control
- Mouse-wheel volume control
- Middle-click mute
- Maximum-quality preference
- Interactive overlay visibility controls
- Customizable player-control accent color
- Optional ad-block status indicator
- Recovery for selected Twitch/Firefox playback failures

## Firefox support

The initial public release targets **Firefox desktop**.

- Minimum Firefox version: **142**
- Firefox for Android is not currently supported
- Better Player does not run in Firefox Private Windows in the initial release

The Firefox Add-ons listing has been submitted for review. A direct store link will be added here when the listing is public.

## Privacy

Better Player has no developer-operated analytics, advertising, tracking, or telemetry service.

Playback-related requests are sent only to Twitch-operated services as required for Twitch playback functionality. Settings and per-channel audio profiles are stored locally in Firefox.

See the [Privacy Policy](PRIVACY_POLICY.md) for details.

## Support

If something is not working, see [SUPPORT.md](SUPPORT.md) first.

You can also:

- [Open a bug report](../../issues/new?template=bug_report.yml)
- [Request a feature](../../issues/new?template=feature_request.yml)
- [View existing issues](../../issues)

When reporting playback problems, please include your Firefox version, Better Player version, steps to reproduce the problem, and whether another Twitch/ad-blocking extension is enabled.

**Do not post Twitch cookies, authorization headers, session tokens, or other account credentials in an issue.**

## Known limitations

Twitch changes its player and internal services regularly, so playback-related behavior can occasionally require maintenance.

Ad delivery is controlled by Twitch. Cleaner playback during an ad break depends on the playback options Twitch makes available at that time.

Do not run Better Player alongside another extension that also modifies Twitch's stream-level video-ad playback. Multiple extensions acting on the same playback pipeline can interfere with one another.

## Licensing and third-party software

Better Player contains code derived from **Alternate Player for Twitch.tv** by Alexander Choporov (CoolCmd), distributed under the BSD 3-Clause License.

Its native Twitch ad-handling component contains code derived from the MIT-licensed **TwitchAdBlock / TwitchAdSolutions** projects.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for attribution and upstream information.
