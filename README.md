# @koehler8/cms-theme-southpark — Alpine Dawn

- **Slug**: `southpark`
- **Version**: 1.0.1
- **Author**: koehler8

## Install

```bash
npm install @koehler8/cms-theme-southpark
```

```js
// vite.config.js
import cms from '@koehler8/cms/vite';

export default {
  plugins: cms({ siteDir: './site', themes: ['@koehler8/cms-theme-southpark'] }),
};
```

Set `site.theme` to `"southpark"` in your site config. If CDN font access is restricted, host the Google Font files locally and adjust the import.

## Visual Direction
- Pastel alpine palette with warm sunlight gradients, cool sky blues, and charcoal cards for contrast.
- Light body canvas paired with dark cards and amber highlights keeps legal/operations pages readable while preserving a playful hero look.
- CTA gradients blend sky blue→green→amber; badges and chips lean on sunshine yellows.

## Token Highlights
- Card/chrome tokens favor semi-transparent dark overlays with creamy text; helper/tabs/fields mirror the same contrast rules.
- Countdown/status/chart tokens emphasize amber digits over dark cards; modal surfaces stay light for accessibility.
- Input/field tokens include explicit focus/placeholder colors plus `field-group` overrides to keep forms consistent across legacy components.

## Compatibility Notes
- Great for playful consumer drops or outdoor-inspired brands; pair with photography or illustrated scenery.
- The theme sets background-attachment fixed on `body` to keep gradients anchored—avoid layering conflicting site-level backgrounds unless you remove or override that rule.

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## License

[MIT](./LICENSE)
