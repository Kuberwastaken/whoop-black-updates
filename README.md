# whoop-black-updates

The public update feed for WHOOP BLACK, a private personal build. The app reads
[`latest.json`](latest.json) at most twice a day to tell its user when a newer version is out:

```json
{"version": "1.4.0", "url": "https://github.com/…/releases/tag/v1.4.0", "notes": "One line about the release."}
```

There is nothing else here: no APKs, no code, no analytics. Releases themselves are private.
