# Jellyfin Acrylic

Dark Acrylic theme for Jellyfin Web. Violet accent, frosted header and menus, Geist for text, Geist Mono for code.

## Install

In Dashboard, then Branding, then Custom CSS, paste:

```css
@import url("https://cdn.jsdelivr.net/gh/iShark5060/Jellyfin-Acrylic@main/theme.css");
```

That line has to stay first. Hard-refresh after a change. jsDelivr and the browser both cache the file.

This styles Jellyfin Web and clients that load it. The admin dashboard on 10.11 and later ignores custom CSS. Native apps that draw their own interface do not pick it up.

Fonts load from jsDelivr, so the browser has to reach that CDN.

## License

[MIT](LICENSE)
