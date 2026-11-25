---
title: Coffee Time Backup Privacy Policy
---

# Privacy Policy

Last updated: November 25, 2026

## Purpose

Coffee Time Backup is a personal backup integration operated by
Brent Coggan for his own privately hosted Coffee Time application.

It is not a public service and does not accept other users.

## Google Drive access and use

The integration uses rclone to access the owner's Google Drive
for backup purposes.

It reads file metadata, lists and compares backup files, uploads
database archives, application configuration, certificates, and
coffee photographs, and removes expired backup files according
to the configured retention policy.

Although the requested Google Drive permission permits broad
file access, the configured backup job targets the
"BrewLog Backups" folder.

## Storage and security

Backup source files and OAuth credentials are stored on the
owner's private computer systems. Remote backups are stored
in the owner's Google Drive account.

Backup files, OAuth tokens, client secrets, and private keys
are not published on this website or in its public repository.

## Sharing

The operator does not sell Google user data, use it for
advertising, or intentionally disclose it to unrelated third
parties. Google provides the remote backup storage.

## Retention and deletion

Daily backup archives are subject to the configured retention
policy, currently approximately 30 days. Photo backups are
maintained separately and may be retained longer.

The owner can delete backups from Google Drive and revoke the
integration's access through Google Account settings.

## Website hosting

This informational website is hosted on GitHub Pages.
GitHub may collect visitor information under its own privacy
policy. This site does not intentionally add analytics or
advertising trackers.

## Contact

Brent Coggan
bcoggan@gmail.com

[Home](index.html)
