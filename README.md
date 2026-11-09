# Venpadi landing page

The marketing site for [Venpadi](https://github.com/Venpadihq/venpadi), vendors padi: a record-keeping app for Nigerian vendors.

One static page, no build step. `index.html` holds the markup, styles and script; `assets/` holds the Figma exports, the app screenshots shown inside the 3D phone, and the app icon.

## Run it locally

```sh
python3 -m http.server 8090
# open http://localhost:8090
```

## Deploy

GitHub Pages from the `main` branch, root folder. `.nojekyll` is present so Pages serves the files as they are.

## Things to fill in

- `STORE_LINKS` near the top of the script in `index.html`: the Google Play and App Store URLs. Until they are set, the "Get the app" sheet tells visitors to search the store.
- `assets/screens/*.jpg` are screenshots of the running app; recapture them when the app's screens change.
