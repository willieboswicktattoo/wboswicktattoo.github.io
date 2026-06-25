# Willie Boswick Tattoos

🌐 **Live site: https://willieboswicktattoo.github.io**

---

## Site Structure

```
index.html          — Home page
tattoos.html        — Tattoos & Flash gallery
shop.html           — Shop page
css/style.css       — All styles
js/main.js          — Home page script
js/tattoos.js       — Gallery + lightbox script
images/
  site/             — Hero photos
  tattoos/          — Tattoo photos
  flash/            — Flash designs
  shop/             — Shop item photos
  gallery.json      — Auto-updated list of tattoo/flash photos
shop.json           — Shop items (name, price, image)
```

---

## Adding Tattoo or Flash Photos

1. Go to **https://github.com/willieboswicktattoo/willieboswicktattoo.github.io**
2. Click `images` → then `tattoos` or `flash`
3. Click **Add file** → **Upload files**
4. Drag your photo in
5. Click **Commit changes**

`gallery.json` updates automatically. The site will reflect your new photo in **1-2 minutes**.

Check the **Actions** tab — green checkmark ✅ means it's live.

---

## Adding a Shop Item

Shop items are managed in `shop.json` at the root of the repo.

### Step 1 — Upload the photo
1. Go to `images/shop/`
2. Click **Add file** → **Upload files**
3. Upload your photo (e.g. `print1.jpg`)
4. Commit

### Step 2 — Add it to shop.json
1. Click `shop.json` in the repo root
2. Click the **pencil icon** to edit
3. Add a new entry inside the `[` `]` brackets:

```json
[
  {
    "image": "print1.jpg",
    "name": "Name of the item",
    "price": 30
  },
  {
    "image": "print2.jpg",
    "name": "Another item",
    "price": 45
  }
]
```

4. Click **Commit changes**

The shop updates immediately — no wait needed.

---

## Tips

- File names should have **no spaces** — use dashes (e.g. `rose-print.jpg`)
- Photos should be **JPG or PNG**
- Try to keep photos under **2MB** for fast loading
- Price should be a **number** with no `$` sign (e.g. `30` not `"$30"`)
- feel free to reach out to me at any time if you have trouble!
