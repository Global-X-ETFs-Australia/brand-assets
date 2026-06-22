# Global X brand assets

Public-hosted brand images so they can be embedded as inline `<img>` in GitHub
comments and other markdown (which fetch images anonymously via a proxy and so
cannot reach assets in private repos).

## `globalx_emoji_128.png`

The Global X crossed-swords brand mark — used as MAGIdev's icon on the GitHub
PR/issue comment titles it posts. 128×128 PNG, RGBA, a few KB.

Canonical raw URL:

```
https://raw.githubusercontent.com/Global-X-ETFs-Australia/brand-assets/main/globalx_emoji_128.png
```

Inline usage in a GitHub markdown comment **body**:

```html
<img src="https://raw.githubusercontent.com/Global-X-ETFs-Australia/brand-assets/main/globalx_emoji_128.png" height="16" alt="MAGIdev"> MAGIdev ...
```

For plain-text channels (Slack/Teams `notify()` webhook payloads) where an image
will not render, use the Unicode `⚔️` as the brand-consistent text fallback.
