# Smart DJ — Support

Smart DJ picks the right playlist for right now, on Apple Music or Spotify, across iPhone, iPad, Mac, Apple TV, and Apple Watch.

This page is here to help if you're stuck. If you don't find your answer below, contact us at **admin@5-scotts.com** and we'll help you out.

## The Five Play Modes

- **Today's Schedule** — plays whatever mode you've assigned to today's weekday in Settings → Weekly Schedule.
- **Random** — shuffles across all your eligible playlists.
- **Favorite** — picks randomly from playlists you've marked as favorites.
- **Discovery Station** — plays your personalized discovery mix, right in the app.
- **New Music Station** — plays the latest releases picked for you.

Random and Favorite avoid repeating a playlist you've heard in your last 10 plays, and automatically skip Christmas playlists outside of December.

## Getting Started

### Apple Music

The first time you play something or import playlists, Smart DJ will ask for permission to access your Apple Music library. Allow it when prompted — this is Apple's standard system permission, not something Smart DJ controls.

### Spotify

Because Spotify's API requires every app to register its own credentials, connecting Spotify takes a couple of extra steps the first time:

1. Go to [developer.spotify.com/dashboard](https://developer.spotify.com/dashboard) and log in with your Spotify account.
2. Create a new app (any name/description is fine).
3. In the app's settings, set the **Redirect URI** to exactly: `smartdj://spotify-callback`
4. Copy the app's **Client ID**.
5. In Smart DJ, go to Settings → paste the Client ID into the Spotify field → tap **Connect Spotify** and log in.

Playing music via Spotify requires the Spotify app to be open and active on one of your devices (a Spotify Premium account is required for playback control, per Spotify's own API rules).

## Weekly Schedule

Settings → Weekly Schedule lets you assign a different mode to each day of the week. This only affects the **Today's Schedule** button — the other four modes always work the way you'd expect regardless of what day it is.

## Favorites & Christmas Playlists

Mark any playlist as a Favorite from the Playlists screen so **Favorite** mode can pick it. Playlists marked **Christmas** are automatically excluded from Random/Favorite rotation for the rest of the year, and automatically included every December.

## History

Smart DJ remembers your last 10 plays so Random and Favorite modes don't repeat themselves right away. Clear it anytime from Settings if you want a fresh start.

## Backup & Restore

Settings → Backup lets you export a snapshot of your favorites, Christmas playlists, history, saved links, and weekly schedule as a file you can keep or move to another device. Import restores from a previous export. This is a manual snapshot you control — it isn't automatic, and we never receive a copy of it.

## Everywhere You Are

Your favorites, history, saved links, and weekly schedule sync automatically across your devices through your own iCloud account — nothing to set up, it just works as long as you're signed into iCloud on each device.

- **iPhone** — full app with all five modes
- **Mac** — full app with all five modes, plus a table view for managing playlists
- **Apple TV** — full app with all five modes
- **Apple Watch** — play any mode or playlist; Discovery/New Music Station open directly in Apple Music since Apple Watch has no in-app music player

### CarPlay

Connect your iPhone to CarPlay and Smart DJ appears with all five play modes, ready to tap from your car's display.

### Siri & Shortcuts

Try "Hey Siri, play Smart DJ" or "Play Discovery Station with Smart DJ." All five modes are also available as Shortcuts you can combine into your own automations.

## Troubleshooting

**"No eligible playlists were found."**
This means every playlist that qualifies for the mode you picked (e.g., all your Favorites) has been played recently or is a Christmas playlist outside of December. Try again, add more playlists to that category, or clear your history in Settings.

**Spotify won't play / "No active device."**
Open the Spotify app on your phone or another device first so there's an active Spotify Connect session, then try again from Smart DJ.

**Discovery Station or New Music Station says a link is missing.**
These two rely on a saved catalog link. Open the playlist editor for that entry and make sure a link is saved (Apple Music catalog link or Spotify link/URI, depending on your connected service).

**Tapping "Open in Apple Music" doesn't show what's playing.**
Make sure you're on the latest version of Smart DJ — this was fixed to link directly to the currently playing track rather than Music's Home tab.

## Privacy

Smart DJ has no account system, no analytics, and no ads. See our full [Privacy Policy](PRIVACY_POLICY.md) for details on how Apple Music, Spotify, and iCloud sync work.

## Contact

Questions, bug reports, or feature requests: **admin@5-scotts.com**
