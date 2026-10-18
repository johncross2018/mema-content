# mema-content

Public shelf for the private Mema test. GitHub Pages serves `feed.json` and the approved MP4s in `clips/`.

The approval queue does not live here. Only clips that were approved are copied in, at 720×1280 H.264, and old files are deleted so the site stays under the 1 GB Pages limit.

## Pages

Settings → Pages → Build and deployment → Source: GitHub Actions.

The workflow in `.github/workflows/pages.yml` publishes the repository root.

Feed URL: `https://johncross2018.github.io/mema-content/feed.json`

## Testers

The arm64 and armv7 APKs are attached to a GitHub Release on this repo. The install links are the release asset URLs.
