# Deploying this page

`index.html` is fully self-contained — all CSS and JavaScript are inline, there are no external requests, no fonts to load, no build step, and no dependencies. Drop it on any static host and it works.

## Fastest options

**Netlify Drop** — https://app.netlify.com/drop
Drag the folder onto the page. Live in about ten seconds on a random `*.netlify.app` URL. No account needed to start.

**Cloudflare Pages** — https://pages.cloudflare.com
Create a project → Direct Upload → drag the folder. Free, fast, and lets you put the whole site behind Cloudflare Access (email-based login) if you'd rather not have a public URL at all.

**GitHub Pages**
Push the folder to a repo, then Settings → Pages → deploy from `main` / root. Note that the *repo* is public unless you're on a paid plan, even though the page content is generic.

**Vercel** — `npx vercel` in the folder, or drag-and-drop at vercel.com.

All four give you a free HTTPS URL. Point a custom domain at it later if you want.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site. This is the only file that's strictly required. |
| `robots.txt` | Asks search engines not to index the page. Delete it if you want the page findable. |

## Notes before you share the link

**It's set to noindex.** `index.html` contains `<meta name="robots" content="noindex, nofollow">` and `robots.txt` blocks crawlers. Given the subject matter that seemed like the right default. Remove both if you'd rather it be discoverable.

**Progress is per-browser, per-device.** Checkboxes, statuses, and notes save to `localStorage`, which means:

- Nothing is uploaded anywhere. There's no backend, no analytics, no tracking.
- Everyone you share the link with gets their own independent copy of the progress state. That's what you want here — you're not sharing a tracker, you're sharing a tool.
- Clearing browser data wipes progress. The **Export progress as CSV** button in the footer is the backup.
- Progress does not sync between someone's phone and laptop.

**The note fields will hold personal data.** People will paste profile URLs and confirmation numbers into them. That data never leaves their machine, but it does sit unencrypted in their browser profile — worth saying out loud if you're sending this to family.

## Editing the content

Everything on the checklists lives in one JavaScript object near the bottom of `index.html`, starting at `const DATA = {`. The shape is:

```js
foundations: [
  { g: "Group heading", t: 1, items: [
      { n: "Item name", u: "https://opt-out-url", w: "Why it matters / how it works" }
  ]}
]
```

- `g` — group heading
- `t` — priority tier, `1`–`3`, which sets the colour of the badge
- `n` — item title (also generates its saved-state key, so renaming an item resets that item's progress)
- `u` — link, or `""` for none
- `w` — the explanatory line underneath

Add, remove, or reorder freely. Progress bars, group counts, the header percentage ring, and the CSV export all recalculate from this object automatically — nothing else needs touching.

To change section headings, intro text, the tables, or the request-letter template, edit the HTML directly; those are plain markup.

## Keeping it current

Opt-out URLs rot. When one 404s, search that site's footer for "Do Not Sell My Personal Information" or "Privacy" — the form is nearly always one click from there. Worth a re-check every six months or so.

The California DROP milestone (1 August 2026, when brokers must begin processing requests) is the main dated claim on the page. Once that's passed, the wording in the "Your rights" section should be updated to past tense.
"# PublicDataRemoval" 
