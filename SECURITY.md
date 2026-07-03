# Security Policy

## Supported Versions

Security reports are accepted for the latest public Anchor macOS release and
for this public website repository.

Older Anchor releases may no longer receive fixes after a newer signed release
is available. Please update to the latest version before reporting an issue
that may already be fixed.

## Reporting a Vulnerability

Please report security issues privately by emailing:

`haichaoli616@gmail.com`

Include as much detail as you can safely share:

- Affected Anchor version or website URL
- macOS version and device type, if relevant
- Steps to reproduce the issue
- Expected and actual behavior
- Any logs, screenshots, or proof-of-concept files that do not expose private
  user data

Please do not publicly disclose a vulnerability until there has been reasonable
time to investigate and ship a fix.

## Scope

Security-sensitive areas include:

- Screen Recording, Camera, and Notification permission handling
- Local screenshot and focus-session processing
- App updates and release downloads
- Crash and anonymous analytics configuration
- Website links, release metadata, and appcast update metadata

Anchor should never upload screen contents, camera input, goals, notes, or work
content during local proctor modes. Reports suggesting otherwise are treated as
high priority.

## Response Expectations

I aim to acknowledge security reports within 7 days and provide a status update
as investigation progresses. Fix timelines depend on severity, reproducibility,
and Apple/macOS release requirements.
