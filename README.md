# new-releases-feed

A small, machine-generated JSON feed of upcoming book releases (roughly the next six months), with 300px cover thumbnails. It is used by a personal e-reader plugin.

- `feed.json` - the list of books (title, author, release date, genres, short description, cover path)
- `covers/` - resized cover images

The feed is rebuilt automatically once a week. Data comes from public sources (publisher/retailer release listings and public book databases such as Hardcover and Open Library). It contains no personal data.
