# Guide

## Prepare

Update files: `ionic.config.jcon`, `capacitor.config.json`, `src/config.ts`
Change logo:
`resources/icon.png`,
`resources/splash.png`,
`resources/android/icon-background.png`,
`resources/android/icon-foreground.png`
Generate files: `cordova-res android --skip-config --copy`
## Build

- `yarn build`
- `npx cap copy`
- `npx cap open android`

