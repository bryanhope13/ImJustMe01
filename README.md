# I'm Just Me (ImJustMe01)

Website for **I'm Just Me LLC**, the Indianapolis apparel brand founded by Kyle Hope in 1991 to promote a message against racism and stereotyping.

It's a single static page (`index.html` plus `images/`) with no build step, so it can be hosted on GitHub Pages.

## Updating shop and social links

When the Etsy shop and social accounts go live, open `index.html` and fill in the `LINKS` object near the top of the script:

```js
const LINKS = {
  etsy: "",
  facebook: "https://www.facebook.com/imjustme01/",
  instagram: "",
  tiktok: ""
};
```

Links left empty stay hidden. Adding the Etsy link switches the shop button to "Shop on Etsy".

## Hosting on GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`.
