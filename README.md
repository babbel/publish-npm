# GitHub Action `babbel/publish-npm`

Publishes JavaScript npm package to GitHub Packages.

## Usage

```
    steps:
      - uses: babbel/publish-npm
```

You can also specify a `tag` input to register the published package with, such that `npm install <name>@<tag>` will install this version
```
    steps:
      - uses: babbel/publish-npm
        with:
          tag: beta
```
