# Pixel Disc – Privacy Policy

_Last updated: 26 November 2026_

Pixel Disc is a music player for Android that plays the music stored on your own device.
It is made by ReOpHyVa. This page explains what data the app uses and when anything leaves
your phone.

## The short version

- Your music, playlists, favourites, play counts and listening history stay **on your device**.
- Pixel Disc has **no ads, no analytics, no tracking** and no user accounts.
- Only two optional features ever send anything about your music over the internet, and both
  are **off unless you turn them on**:
  1. **Artist photos & bios** (sends artist names to Wikipedia)
  2. **Claude for AI Mix** (sends your request and a song list to Anthropic, using your own key)
- To offer updates, the app checks GitHub **at most once a day** for a newer version. This sends nothing
  about you or your music, and you can turn it off.

## What stays on your device

- **Your music library:** the app reads audio files on your device to build your library. The
  files are never uploaded.
- **Lyrics:** lyrics are read **only from your own files**: lyrics embedded in the song file,
  a `.lrc` file with the same name next to the song, or a `.lrc` file you pick yourself.
  Pixel Disc never looks up lyrics online.
- **Playlists, favourites, play counts, listening history and settings** are stored in the
  app's private storage.
- **Diagnostics log:** errors and crashes are recorded on your device only. Nothing is sent
  anywhere unless you choose to copy or share the log yourself.

## Optional features that use the internet

### Artist photos & bios (Wikipedia)

Off by default. You can turn it on during setup or in **Settings → Library**.

When it's on, Pixel Disc sends the **names of artists in your library** to Wikipedia (run by the
Wikimedia Foundation) to find a short biography and a freely licensed photo. The results are
saved on your device and credited to their authors. No other information about you or your
music is sent.

Like any website, Wikipedia can see your device's **IP address** and the app's name and version
when these requests are made. See the
[Wikimedia Foundation Privacy Policy](https://foundation.wikimedia.org/wiki/Policy:Privacy_policy).

### Claude for AI Mix (Anthropic)

AI Mix works fully on your device by default. Only if you **add your own Anthropic API key**
and turn on **Use Claude for AI Mix** (Settings → General → AI features), then each time you
create an AI mix Pixel Disc sends to Anthropic:

- the text of your request (for example "chill evening, 1 hour"), and
- a list of up to 700 songs from your library: title, artist, genre, year, length, whether the
  song is hi-res, whether it's one of your favourites, and an internal song number (used only to
  match Claude's answer to your songs; it means nothing outside your phone).

This is sent directly from your device to Anthropic's API using **your** key; it does not pass
through any server of ours. Anthropic can see your device's **IP address**. Your use of the API
is covered by your agreement with Anthropic and the
[Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy).

Your API key is stored only on your device, encrypted with a key kept in Android's secure
key storage (Android Keystore). It is never included in Pixel Disc's backup files
and is excluded from Android's automatic Google backup.

If you turn off **AI features** entirely, the app makes no AI requests at all.

### Update checks (GitHub)

On by default; you can turn it off in **Settings → About → Check for updates automatically**.

At most once a day when you open the app, and whenever you tap **Check now**, Pixel Disc downloads a small file
(`version.json`) from the public Pixel Disc releases page on GitHub to see whether a newer
version exists. If you choose to update, the new app file is downloaded from GitHub too.
No information about you, your device or your music is sent; like any website, GitHub can see
your device's **IP address** and the app's name and version. See the
[GitHub Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).

Updates are installed only when you agree, and only after the app has checked that the file is
genuine (its checksum, and that it's signed by the Pixel Disc developer).

## Backups

- **Pixel Disc backups** (Settings → General → Backup & restore) are saved where you choose:
  the app's own storage or a folder you pick. They contain playlists, favourites, play counts,
  listening history and settings, never your API key. Pixel Disc does not upload them anywhere.
- **Android's own backup:** if you have Google backup turned on for your phone, Android may
  back up the app's settings and data to your Google account, as it does for most apps. This
  includes the on-device diagnostics log, which contains your phone's make and model, Android
  version and app version. Your API key is excluded.

## Permissions

- **Music and audio:** to find and play the music on your device.
- **Notifications:** to show playback controls in the notification shade and on the lock screen.
- **Internet:** used only for the optional features above and for update checks.
- **Install apps:** used only to install a Pixel Disc update you've agreed to.
- **Foreground service and wake lock:** keep music playing with the screen off, and finish an
  update download in the background.
- **Run at startup:** lets scheduled backups and update checks continue after the phone restarts.
- **Network state:** checks whether you're online before using the optional internet features.

## Your rights (GDPR, Jordan's Personal Data Protection Law, CCPA)

Depending on where you live, laws such as the EU GDPR, Jordan's Personal Data Protection Law
(Law No. 24 of 2023) and the California Consumer Privacy Act give you rights over your personal
data, such as access and deletion. Pixel Disc has no servers and holds no data about you, so
there is usually nothing for us to give or delete: everything is on your device, and you can
delete it by clearing the app's data or uninstalling it. For any question or request, write to
the contact address below. Pixel Disc does not sell or share personal information.

## Children

Pixel Disc is not directed at children and does not knowingly collect any personal information
from anyone.

## Changes

If this policy changes, the new version will be published at this address with a new
"Last updated" date.

## Contact

Questions or feedback: **pixeldisc.support@gmail.com**
