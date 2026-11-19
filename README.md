# Manual guides

Field guides for Exodigo tools, served by GitHub Pages; the site root lists them, each guide has its own folder.

- **Hammer Box v2 · ExoTerra field guide** (Hebrew / English): `hammer-box-v2/` (`index.html` + `img/`).
  The app's "User guide" button opens it with `?lang=he|en`.

## Updating the ExoTerra guide

The source lives in the app repo (`exoterra_app/docs/field-guide/exoterra_guide.html`):

```
python exoterra_app/tools/guide_site.py      # writes docs/field-guide/index.html
copy docs/field-guide/index.html and docs/field-guide/img/ into hammer-box-v2/, commit, push
```

GitHub Pages republishes within a minute or two of the push.
