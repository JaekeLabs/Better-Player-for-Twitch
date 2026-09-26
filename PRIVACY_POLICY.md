# Privacy Policy for Better Player for Twitch

**Effective date: 2026-09-25**

Better Player for Twitch is an independent Firefox extension maintained by JaekeLabs. It is not affiliated with or endorsed by Twitch Interactive, Inc.

The extension enhances Twitch's native web player with ad replacement, audio controls, brightness controls, quality preferences, overlay controls, and related playback features.

## Data used for core functionality

Better Player operates only on Twitch pages covered by its Firefox manifest.

To provide its playback and ad-replacement features, the extension may process and transmit the following data to Twitch-operated services:

- **Authentication information:** Twitch authentication, device, session, and integrity values already available to the Twitch page may be read from Twitch requests and reused for Twitch playback or metadata requests.
- **Browsing activity:** the current Twitch channel or Twitch page context may be used to request the correct stream metadata, playback token, playlist, or protected-stream status.

These transmissions are required for the extension's primary Twitch playback functionality.

Better Player does **not** transmit mouse movement, wheel events, clicks, keystrokes, or other general website-interaction data as extension telemetry.

## Network requests

The extension communicates only with Twitch's API and media-delivery infrastructure for its playback features, including Twitch GraphQL and Twitch playlist/media endpoints.

The extension does not send user data to a JaekeLabs server and does not use independent analytics, advertising, crash-reporting, or tracking services.

## Local storage

Better Player stores extension preferences locally in Firefox, including settings such as:

- whether the extension is enabled;
- player-control appearance;
- brightness and volume-control preferences;
- global compressor settings;
- per-channel compressor overrides;
- per-channel equalizer state and band values;
- quality and overlay preferences.

Per-channel audio profiles are stored in Firefox extension storage so they can be restored when the user returns to that Twitch channel.

The ad-replacement engine may also use Twitch page storage for playback-related state, such as the maximum-quality preference, and session storage for a short-lived cache of protected/encrypted Twitch channels.

Authentication/session values captured from Twitch requests are not intentionally persisted in Better Player's extension settings.

## Private browsing

The initial public release does not run in Firefox Private Windows. This prevents persistent per-channel settings from recording Twitch browsing activity from a private-browsing session.

## Data sharing and sale

JaekeLabs does not sell user data.

Better Player does not transmit collected data to independent third parties. Data required for Twitch playback is sent only to Twitch-operated services as part of the extension's primary function.

## Data retention and deletion

Extension settings and per-channel audio profiles remain on the user's device until they are changed, cleared, or the extension's stored data is removed.

Session-only playback state expires with the applicable browser/tab session.

Uninstalling the extension or clearing its extension storage removes Better Player's persisted settings.

## User control

Users can disable or uninstall Better Player at any time from Firefox Add-ons Manager.

The extension also provides an in-page enable/disable control for its Twitch enhancements.

## Changes to this policy

This policy may be updated when Better Player's functionality or data handling changes. The current policy is maintained in this public repository.
