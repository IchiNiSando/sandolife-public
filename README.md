# Sando public downloads

Installers and public files for Sando products. Source code stays in private repos.

## Patreon Batch

Download, pricing, and setup instructions: **https://patreon-batch.sandolife.site**

(Download links aren't duplicated here — they're versioned and change every release, so the site is the source of truth. Linking a specific filename from this README goes stale the moment a new version ships.)

Mac builds are not Apple-notarized. Open the DMG and double-click **Install and Open.command** — do not launch the `.app` from the disk image.

If macOS says **Apple could not verify "Patreon Batch.app" is free of malware**: click **Done**, then System Settings → Privacy & Security → **Open Anyway**. Or:

```bash
xattr -cr "/Applications/Patreon Batch.app"
"/Applications/Patreon Batch.app/Contents/MacOS/Patreon Batch"
```
