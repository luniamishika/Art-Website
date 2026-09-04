# Misha Lunia

Artist site for ceramics and a small shop.

**Pages**

- [Art gallery](index.html)
- [Shop](shop.html) — cups and mugs
- [About](about.html)

Instagram: [mishaisnotdeadyet](https://www.instagram.com/mishaisnotdeadyet/)  

## Run locally

From this folder:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Add a gallery photo

Put the file in `images/gallery/` (jpg, png, or webp). Name it after the piece, like `bowl.png`. Then run:

```bash
python3 build-gallery.py
```

That adds it to the art gallery and creates `work/bowl.html` if it does not exist yet. You can edit that page for the write-up and extra photos. If you push a new image without running the script, GitHub will build the page for you.
