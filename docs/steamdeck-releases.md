# Steam Deck / Linux Releases

This page documents Linux x86-64 and Steam Deck AppImage releases for the Project Stonehenge fork.

**Download page:** https://github.com/omegakatana92/ProjectStonehenge-Steam-deck/releases

## Current status

No release has been published yet. The Linux port and AppImage must be built and validated before a downloadable release is created.

## Release checklist

1. Confirm native Linux build and automated tests pass.
2. Verify launch, Vulkan rendering, audio, controls, ISO selection, and persistent saves on Steam Deck.
3. Package `ProjectStonehenge-SteamDeck-x86_64.AppImage` and test it outside the build container.
4. Confirm the AppImage contains no copyrighted Ace Combat 04 ISO, assets, or extracted game files.
5. Include GPL-3.0 and required third-party notices, source/commit information, installation instructions, known issues, and verification status.
6. Publish a versioned GitHub release on **this fork**, uploading the tested AppImage as a release asset. Use a prerelease label for incomplete or experimental builds.

## Installation (once a verified AppImage exists)

Download the AppImage from the Releases page and make it executable:

```bash
chmod +x ProjectStonehenge-SteamDeck-x86_64.AppImage
./ProjectStonehenge-SteamDeck-x86_64.AppImage
```

Provide your own legally obtained, supported North American Ace Combat 04 ISO. No game data is included.

## Attribution

Original project: https://github.com/Onaga00/ProjectStonehenge

This fork is an unofficial Linux / Steam Deck adaptation. Preserve original authorship, GPL-3.0 license and third-party notices. No affiliation with Bandai Namco.
