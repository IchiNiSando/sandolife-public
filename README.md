# Sando public downloads

Installers and public files for Sando products. Source code stays in private repos.

## Patreon Batch

| File | Platform |
|---|---|
| [PatreonBatch-arm64.dmg](https://github.com/IchiNiSando/sandolife-public/releases/latest/download/PatreonBatch-arm64.dmg) | Mac Apple silicon |
| [PatreonBatch-x64.dmg](https://github.com/IchiNiSando/sandolife-public/releases/latest/download/PatreonBatch-x64.dmg) | Mac Intel |
| [PatreonBatch-Setup.exe](https://github.com/IchiNiSando/sandolife-public/releases/latest/download/PatreonBatch-Setup.exe) | Windows x64 (when published) |

Site: https://patreon-batch.vercel.app

Mac builds are not Apple-notarized. Open the DMG and double-click **Install and Open.command** — do not launch the `.app` from the disk image.

If macOS says **Apple could not verify “Patreon Batch.app” is free of malware**: click **Done**, then System Settings → Privacy & Security → **Open Anyway**. Or:

```bash
xattr -cr "/Applications/Patreon Batch.app"
"/Applications/Patreon Batch.app/Contents/MacOS/Patreon Batch"
```

### How to get a license

1. Download the installer for your machine.
2. Open the app → **Plan → Start 7-day trial** (one email, one computer) or **Subscribe**.
3. Stripe test cards: `4242 4242 4242 4242`. After payment, paste the `pb_…` key under **Enter license**.
