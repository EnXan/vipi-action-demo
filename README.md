# vipi-action demo

Demo repository for [vipi-action](https://github.com/EnXan/vipi-action), the
GitHub Action of [VIPI](https://github.com/EnXan/VIPI). Its only workflow,
[`.github/workflows/vipi-scan.yml`](.github/workflows/vipi-scan.yml), is the
README example with `pr-comment: true`: every pull request that adds or
changes images is scanned for visual prompt injections, and the result is
posted as a comment.

The open demo pull request adds VIPI's three
[sample images](https://github.com/EnXan/VIPI/tree/main/examples), two of
which contain a prompt injection, so its scan fails. It is not meant to be
merged.
