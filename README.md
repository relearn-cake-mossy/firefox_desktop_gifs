# Desktop GIFs for Firefox

Firefox port of the [original Desktop GIFs project](https://github.com/rayytor/desktop_gifs).

Post GIFs in YouTube comments and replies from Firefox desktop.

## Install

The ready-to-load Firefox add-on is [`firefox/desktop-gifs.xpi`](firefox/desktop-gifs.xpi).

To try it temporarily, open `about:debugging#/runtime/this-firefox`, choose **Load Temporary Add-on…**, and select `firefox/manifest.json`. Temporary add-ons are removed when Firefox closes.

For a permanent Firefox installation, the add-on must be signed by Mozilla. Upload the XPI to Mozilla Add-ons for signing, then install the signed package.

Requires Firefox 128 or newer.

## Use

1. Sign in to YouTube and open a video or a Short.
2. Click **Add a comment…**, or **Reply** under a comment. A **GIF** button appears next to the emoji button.
3. Click it. The picker opens with Tenor's featured GIFs.
4. Find a GIF by typing a search or pasting a Tenor link (`tenor.com/view/…`, a `media.tenor.com` file link, or a bare Tenor ID).
5. Click a GIF to post it. Anything already typed in the comment box is posted with it.

Press <kbd>Enter</kbd> to post when the picker shows exactly one result, or <kbd>Esc</kbd> to close it. If YouTube does not send the comment automatically, the picker asks you to press the Comment button. If the post fails, nothing is published and your text stays in the box.

## Limits

- **Unofficial.** This project is not affiliated with YouTube, Google or Tenor. It sends a field that YouTube's desktop site does not use itself, so it can stop working whenever YouTube changes something. Use is at your own risk under YouTube's Terms of Service.
- **Tenor only.** YouTube's GIF comments take Tenor GIFs. Tenor closed its public API in June 2026, so search results are read from Tenor's web pages and may break if those pages change. Pasting a link keeps working without search.
- **GIFs only.** Stickers and still images are left out of the results.
- **New comments and replies only.** You cannot add a GIF while editing a comment or writing a channel post.

## Privacy

The extension requests access to `tenor.com` for search. It collects nothing, stores nothing and has no analytics. Search requests go to Tenor without your cookies, and GIF previews load from Tenor's media servers. It never reads your YouTube credentials; YouTube's own page sends the comment.

## License

Copyright (C) 2026 rayytor. This program is licensed under the GNU General Public License, version 3. See [LICENSE](LICENSE).
