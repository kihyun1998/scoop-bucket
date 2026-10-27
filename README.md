# kihyun1998 Scoop bucket

A [Scoop](https://scoop.sh) bucket for [kihyun1998](https://github.com/kihyun1998)'s CLI tools.

## Usage

```powershell
scoop bucket add kihyun1998 https://github.com/kihyun1998/scoop-bucket
scoop install jtic
```

Update:

```powershell
scoop update jtic
```

## Tools

| Name | Description |
|------|-------------|
| [`jtic`](https://github.com/kihyun1998/just-tic) | One-line CLI showing how many lines you added/removed (+/-) in today's git commits |
| [`just-shield`](https://github.com/kihyun1998/just-shield) | Pre-execution supply-chain scanner for GitHub Actions workflows |
| [`just-fetch`](https://github.com/kihyun1998/just-fetch) | Fetches every git clone in a folder, shows how each stands against its upstream, and fast-forwards the ones you pick |

To add a new tool, drop another manifest `.json` into `bucket/`.

## Auto-update

`.github/workflows/auto-update.yml` runs hourly, polls each tool's latest GitHub release (public API, no auth), and refreshes the manifest's URL and SHA256 automatically — no personal access token required.
