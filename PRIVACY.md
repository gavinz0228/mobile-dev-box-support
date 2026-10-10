# DevBoxMobile Privacy Policy

Last updated: October 9, 2026

DevBoxMobile does not collect, sell, or transmit personal information to the
developer. Server profiles, request history, preferences, and task history are
stored on the device. On iOS, credentials and private keys are stored in Apple
Keychain. On Android, saved passwords and SSH private keys are encrypted locally
with AES-GCM using a key held in Android Keystore. Saved command bookmarks and
database profiles and queries are also encrypted on Android. Saving database
passwords is optional. The app does not include advertising or
developer-operated analytics services.

The app connects only to servers, service providers, and identity providers
that the user explicitly configures. Those services process data under their
own policies. Apple may process diagnostics, purchases, and TestFlight feedback
according to the user's Apple settings and Apple's privacy policy.
Google Play, Android and device vendors may process installation, diagnostics
and testing information under their own policies and the user's settings.

Local discovery looks for services on the user's network. The Android app does
not automatically save discovered servers. An optional Android foreground
notification allows users to manage and disconnect active connections; it does
not guarantee survival after process termination.

## Files and backups

Uploads, downloads, CSV exports and manual encrypted backups are stored in
locations chosen by the user. A selected cloud document provider may process
files according to its own policies. The developer cannot recover a manual
backup password. Exported files remain outside the app until the user deletes
them.

On iOS, optional iCloud backup uploads an AES-GCM encrypted archive to the user's
private iCloud database. Its key syncs through iCloud Keychain. Apple processes
this data under its own policies; the developer does not receive the backup.
On Android, automatic system backup is disabled. Automatic Google Drive backup
and cloud synchronization are not included in the current Android version.

## Deletion and support

Deleting the app removes its local app data. Keychain items may persist across
reinstallation and can be removed from DevBoxMobile's Credentials screen before
deleting the app.
Uninstalling the Android app removes its private local data. Uninstalling either
app does not remove exported files, cloud backups, remote files or remote tmux
sessions; users must remove those in their respective locations.

Privacy questions can be submitted through
[GitHub Issues](https://github.com/gavinz0228/mobile-dev-box-support/issues).
Issues are public. Do not include personal information, passwords, keys, tokens,
or private server details. For sensitive concerns, follow the support
repository's [security guidance](https://github.com/gavinz0228/mobile-dev-box-support/blob/main/SECURITY.md).
