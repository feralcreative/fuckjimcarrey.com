# fuckjimcarrey.com

A single-page site hosting a profoundly racist clip of Jim Carrey in brownface playing Iraqi rock star "Johnny Abdul" on [_In Living Color_ s02e13](https://www.imdb.com/title/tt1028234/?ref_=ttep_ep_13) (January 13, 1991) — during the [Gulf War](https://en.wikipedia.org/wiki/Gulf_War).

![Johnny Abdul](./media/poster-johnny-abdul.jpg)

## Structure

```text
/
├── index.html
├── style/
│   ├── style.scss       # source
│   └── style.min.css    # compiled — gitignored
└── media/               # video and image assets
```

## Dev

Compile CSS with:

```bash
sass style/style.scss style/style.min.css --style=compressed
```

Watch mode:

```bash
sass --watch style/style.scss:style/style.min.css
```

## Notes

He's also a longtime anti-vaxxer. Seriously, fuck that guy.
