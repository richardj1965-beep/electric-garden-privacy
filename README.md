# Electric Garden Apps — privacy policies

Static pages, one per app, served by GitHub Pages. No JavaScript, no webfonts, no
third-party requests — the same rule as the apps they describe.

## Publish (once)

The repository must be **public**: GitHub Pages on a private repo needs a paid plan.

```sh
# from this directory
git init -b main
git add .
git commit -m "privacy policies: merge48"
# create the repo on github.com first, then:
git remote add origin git@github.com:<USERNAME>/electric-garden-privacy.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source: Deploy from a branch → `main`, `/ (root)`
→ Save**. First publish takes a minute or two.

## URLs to paste into Play Console

```
https://<USERNAME>.github.io/electric-garden-privacy/merge48.html
```

Check it in a private browser window before pasting. A URL that redirects or 404s is a
common rejection reason, and the Console keeps the value after upload — but a broken link
is a policy problem, not a cosmetic one.

## Adding an app

Copy `merge48.html`, change the title, date and the specifics. Add a line to `index.html`.
Keep the claims true: if an app ever gains a network permission or an SDK, this policy
must change before that build ships.

## Contact address

`merge48.html` uses **electricgarden1965@gmail.com** (the Electric Garden mailbox) in the visible text and the
`mailto:` href. Change both together if it ever moves.
