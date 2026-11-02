# StakeOut ($STAKEOUT)

Single-file static site: `index.html` (no build step).

## Deploy
- **Vercel:** drag this folder / zip contents in, framework "Other", no build command.
- **GitHub Pages:** push `index.html` to the repo root and enable Pages.

## Links
Edit the `CONFIG` object near the top of the `<script>` in `index.html`:

```js
var CONFIG={xUrl:'https://x.com/StakeoutFun',ca:'',buyUrl:'',chartUrl:''};
```

Empty values show a "coming soon" toast instead of a dead link.

## Notes
- All pools, stats, stakes and the night watch log are samples/simulation, saved only in the visitor's browser.
- Not affiliated with Stakehouse.
