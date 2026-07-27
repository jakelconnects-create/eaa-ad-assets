# Everyday AI Academy — ad assets

Public host for Meta ad creatives.

Meta's ads API can only ingest an image from a **publicly reachable URL**; it cannot
accept a local file. This repo exists to give each creative such a URL. Meta fetches
the image once and stores its own copy against an `image_hash`, so the link only has
to resolve at upload time.

Nothing here is secret. These images run as public ads.
