# SleepLab information site

Public information and policies for a private test project for one person.

Live site: <https://mikeuduc.github.io/sleep-lab-info/>

## Edit

This repository is the source for the website. Edit these files directly in
your editor; no copying from another repository is needed.

| File | What it changes |
| --- | --- |
| [index.html](index.html) | Homepage wording |
| [privacy/index.html](privacy/index.html) | Privacy policy |
| [terms/index.html](terms/index.html) | Terms of use |
| [styles.css](styles.css) | Colors, typography and layout |

The site uses plain HTML and CSS. There is no package installation or build step.
Keep the public description general and limited to a one-person test project.

## Preview locally

From this repository's folder, run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open <http://127.0.0.1:8000/>. Save a file and refresh the browser to see changes.
Press Ctrl+C in the terminal to stop the preview.

## Publish

Review your changes, commit the edited files and push to `main`. For example,
after editing the homepage:

```sh
git diff
git add index.html
git commit -m "Update project information"
git push
```

GitHub Pages publishes the root of `main` automatically. Publishing may take
a minute or two. Saving files locally does not change the live website.

Everything committed here is public. Keep personal records, credentials and
private project plans out of this repository.
