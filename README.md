# tiddlybackup

Clone this repo and use the clone in the `GITHTTP_URL`  configuration of [`tiddly/gitbackup`](https://github.com/philips/tiddly/tree/master/gitbackup)

Tiddlers must be tagged with `publish` in order to be pushed publicly. You can customize this in the `tiddlywiki.info` file by removing `tag[publish]`.

## Netlify Setup

Use the Netlify [build configuration](https://docs.netlify.com/configure-builds/get-started/#basic-build-settings) to input these commands:

- **Build Command**: `generate`
- **Publish Directory**: `output/static`
