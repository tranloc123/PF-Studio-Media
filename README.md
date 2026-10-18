# PF Studio Media Library

Public **media-only** download repository for PF Studio Android.

## Distribution design

- GitHub Releases contain original creator-authorized MP4/WebM entrance videos, a real JPEG thumbnail for each video, a SHA-256 checksum list, and a machine-readable `catalog.json`.
- PF Studio fetches a verified catalog via Supabase and downloads selected media from **public Releases**. Videos remain available offline after downloading.
- New packs are published under new immutable release tags. Adding media must not require bundling the new videos into the APK.
- Only media approved for public redistribution may be uploaded. Never include PF Studio application source, private access tokens, signing keys, OAuth secrets, or user data here.
- A thumbnail belongs to its own original video. Future packs must include equivalent thumbnails; no special status for the first 14 videos.

## Status

The first pack (`entrance-pack-v1`) is **pending verified publication**. Empty Releases are not evidence that files were transferred.

## Main app

The PF Studio application source is kept separately in a **private** repository.
