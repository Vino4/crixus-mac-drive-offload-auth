# Crixus Mac Drive Offload

A private, owner-operated rclone setup for uploading and retrieving files from explicitly selected Google Drive folders on the owner's Mac. It uses a dedicated Google Cloud project and desktop OAuth client. It is independent of the SR4710 recording uploader.

Authorization uses Google's folder picker and the `drive.file` scope. The app can access items selected for it and files it creates. It does not request full-Drive access. Folder-rooted rclone destinations provide convenient upload and download locations.

Credentials are stored in an encrypted local rclone configuration, protected by a macOS Keychain-held key. No public service or central file-storage server is operated by this app.

[Privacy policy](PRIVACY.md) · [Terms](TERMS.md)

Contact the owner through this repository's issues.
