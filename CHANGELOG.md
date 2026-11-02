# CHANGELOG — AKABANEKARMX/PROFILE

## RELEASE LOG

```text
$ less /var/lib/AkabaneKarmX/CHANGELOG.log

  [ REV 2.6.1 ] — 2026.11
  :: artifact stills mounted — cam log initialized
  :: cam01 → edumaster-quiz-app · runtime capture (local render, login state)
  :: cam02 → temperature-converter · runtime capture (local render, default state)
  :: treatment · phosphor grayscale + scanlines + grain, consolas telemetry strip

  [ REV 2.6 ] — 2026.11
  :: profile rebuilt as terminal dossier (crt telemetry)
  :: assets/banner-*.svg removed → assets/terminal.svg (single dark crt build)
  :: readme remounted: identity.db block, deployed_artifacts, channels
  :: repo description → tty0 identity dossier line
  :: build stamp corrected: 2026.02 → 2026.11

  [ REV 1.0 ] — 2026.10
  :: initial profile readme (commit 8a31c15) — generic student build
```

## REFRESH PROCEDURE

```text
$ cat /home/AkabaneKarmX/.refresh_rules

  trigger :: real events only — shipped artifact / new stack module / term change
  bump    :: REV stamp in assets/terminal.svg (top-right strip + <title> + aria-label)
  edit    :: boot.log lines in terminal.svg · [ x ] stack list · deploylog in README.md
  verify  :: render assets/terminal.svg to screenshot before pushing
  commit  :: "profile: rev 2.7 — <one event>"
  log     :: append entry above. no calendar refreshes. no fabricated telemetry.
```
