# Content Factory

Content Factory is a personal automation tool that manages my own YouTube
channels end-to-end. It generates topic ideas, scripts, voiceovers,
subtitles, thumbnails, and metadata, then uploads finished videos directly
to my own YouTube channels.

## What the app does

- Generates video ideas, scripts, and metadata (titles, descriptions, tags)
- Produces AI voiceovers and subtitles (English and Tamil content)
- Creates custom thumbnails for videos
- Uploads completed videos, thumbnails, and metadata to YouTube
  using the YouTube Data API

## How it uses Google / YouTube

- The app authenticates with Google OAuth using my own Google account only.
- It uses the YouTube Data API with the `youtube.upload` and
  `youtube.force-ssl` scopes to upload videos, set thumbnails, and
  manage my own channel content.
- The app does **not** access, collect, or store data from any other
  user's YouTube or Google account.

## Data handling

- All processing happens locally on my own computer.
- OAuth tokens are stored locally and used only to access my own channels.
- No data is shared with third parties.

## Contact

For questions about this application, contact: **<aksme.pc@gmail.com>**
