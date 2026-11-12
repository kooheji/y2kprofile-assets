# Y2K Profile shared assets

Versioned theme assets for [Y2K Profile](https://y2kprofile.kooheji.dev), an independent retro profile generator by [kooheji.dev](https://kooheji.dev). This repository serves the shared files used by exported profiles. It does not contain the application source, browser-saved profiles, accounts or user uploads.

## CDN

Release: **v1.0.0**

Base URL:

```text
https://cdn.jsdelivr.net/gh/kooheji/y2kprofile-assets@v1.0.0/public/themes/v1
```

Stylesheet:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/kooheji/y2kprofile-assets@v1.0.0/public/themes/v1/profiles.css">
```

The theme bundle supports MySpace, Friendster, hi5, Windows Live Spaces, Google+ and QZone. It contains the common stylesheet, template interface images, MySpace player movies, recreated mood emoticons, original fictional demo photographs and original demo music. There is no profile database or social-network backend.

## Stable releases

Exports retain their versioned asset URLs. Keep published tags and their files available. Publish a new version for future changes; do not move or replace an existing release tag. GitHub Pages is not required: jsDelivr reads the public GitHub release/tag directly.

`asset-manifest.json` records the size and SHA-256 hash of every shared theme file. The application website and its own fonts/artwork are hosted separately on InMotion.

## Asset sources and notices

- `profiles.css`: the project's reconstructed template styling.
- `myspace/`: supplied historical MySpace interface GIFs and logo; compatibility-patched mini player; a locally recreated skin and original animated mood icons. The archive page, old profile content, ads and archive scripts are excluded.
- `friendster/`: supplied historical Friendster logo.
- `hi5/`: historical interface images and Fives recovered from user-supplied assets, the Wayback Machine and Arquivo.pt.
- `qzone/`: a locally reconstructed sky/star banner using the QZone star shape.
- `demo/`: fifteen AI-generated fictional portraits and album scenes for the Jade Valentine demo. These do not depict real users.
- `media/`: original synthesized demo music. No music recordings have been downloaded from YouTube.

Platform names, marks and archived artwork belong to their respective rightsholders. This is an independent nostalgia project, not an affiliated or endorsed service. Archive availability is not a blanket license; no additional rights in historical third-party assets are granted by publication of this repository. See [LICENSE.md](LICENSE.md) and [the bundled notices](public/themes/v1/THIRD_PARTY_NOTICES.txt). Original generated demo material and recreated mood icons have their usage notices in the corresponding folders. Ruffle is delivered separately from its pinned npm package; its [license](licenses/ruffle-0.7.1-LICENSE.md) and [dependency notices](licenses/ruffle-web-0.7.1-NOTICES.md) are preserved here.

Privacy and rights enquiries: [y2kprofile@kooheji.dev](mailto:y2kprofile@kooheji.dev).
