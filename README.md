# Manual guides

Field guides for Exodigo tools, served by GitHub Pages.

- **ExoTerra field guide** (Hebrew / English): the site root, `index.html` + `img/`.
  The app's "User guide" button opens it with `?lang=he|en`.

## Updating the ExoTerra guide

The source lives in the app repo (`exoterra_app/docs/field-guide/exoterra_guide.html`):

```
python exoterra_app/tools/guide_site.py      # writes docs/field-guide/index.html
copy docs/field-guide/index.html and docs/field-guide/img/ here, commit, push
```

GitHub Pages republishes within a minute or two of the push.
