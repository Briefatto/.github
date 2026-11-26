# Contributing

Briefatto builds design infrastructure for AI agents in the open. Issues, fixes and corrections are welcome in every public repository.

## Where things go

- **Bugs:** open an issue with the bug report form.
- **Ideas and requests:** open an issue with the feature request form.
- **Questions:** ask in the repository's Discussions.
- **Security issues:** never in public. Follow [SECURITY.md](SECURITY.md).

## Pull requests

1. For anything larger than a small fix, open an issue first so the change can be agreed before you build it.
2. Keep one change per pull request, and say what it changes and why.
3. Show how you checked it: the commands you ran, and before and after images for anything visual.

### Briefatto Board

```sh
npm ci
npx playwright install chromium
npm run typecheck
npm test
```

Type checks and tests must pass; CI runs the same steps on every pull request.

### design-md-gallery

Every value in a `DESIGN.md` comes from the brand's rendered site. A correction names the page and viewport where the value can be seen. To ask for a new brand, open a feature request with the brand's site.

## Licence

Contributions are made under the licence of the repository they go to: Apache-2.0 for Briefatto Board, MIT for design-md-gallery. There is no separate agreement to sign.

## Conduct

Everyone taking part follows the [Code of Conduct](CODE_OF_CONDUCT.md).
