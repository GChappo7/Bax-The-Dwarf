# App Assets

Place PNG images and other static assets for the character sheet in this folder.

## Using an image in the app

Reference files with a relative path from `index.html`, for example:

```html
<img src="assets/dwarf-portrait.png" alt="Baxtorian the Dwarf">
```

## Guidelines

- Use short, descriptive, lowercase filenames, such as `bax-portrait.png` or `level-up-icon.png`.
- Keep image paths prefixed with `assets/` when referencing them from `index.html`.
- PNG files with transparent backgrounds are supported.

Git doesn't track empty folders, so this README keeps the folder in the repository until images are added.