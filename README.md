# Nodal Crew — releases

Disk images for [Nodal Crew](https://trynodal.dev/crew), and nothing else. The
source lives in a private repository; this one exists so that the download does
not need an account to reach.

## Download

**[Latest release](https://github.com/Caissaisdead/nodal-crew-releases/releases/latest)**

The asset is named without a version, so this link keeps working:

```
https://github.com/Caissaisdead/nodal-crew-releases/releases/latest/download/Nodal-Crew-arm64.dmg
```

The version is in the release title and in the app's own Info.plist.

## What it needs

- Apple silicon. There is no Intel or universal build.
- macOS 11 or later.
- The Claude Code CLI on your PATH, signed in.

Every image here is signed with a Developer ID, notarised by Apple and stapled,
so it opens without a Gatekeeper warning. If one ever does not, that is a bug
worth reporting rather than a step to click through.

## Updating

There is no auto-update. A new version means downloading a new image.
