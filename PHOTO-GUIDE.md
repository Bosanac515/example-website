# Photo Guide — example.bosatek.com

Replace the placeholder divs with real images by dropping files into the `assets/` subfolders below.
Each filename must match exactly. After adding a photo, find the matching placeholder in the HTML and swap:

```html
<!-- BEFORE (placeholder div) -->
<div class="photo-placeholder pp-construction" style="height:100%;">...</div>

<!-- AFTER (real image) -->
<img src="assets/construction/hero.jpg" alt="Apex Build job site" style="width:100%;height:100%;object-fit:cover;" />
```

---

## construction.html

Folder: `assets/construction/`

| Filename | Dimensions | Description |
|---|---|---|
| `hero.jpg` | 1920×1080 | Hero background — job site aerial, active construction, or completed project exterior |
| `gallery-1.jpg` | 800×1040 | Large featured project photo (left column, spans full height) |
| `gallery-2.jpg` | 600×260 | Project photo — roofing, framing, or interior |
| `gallery-3.jpg` | 600×260 | Project photo — exterior, deck, or remodel |
| `gallery-4.jpg` | 600×260 | Project photo — commercial or residential |
| `gallery-5.jpg` | 600×260 | Project photo — before/after or close-up detail |
| `team.jpg` | 800×600 | Owner portrait or crew photo for the About section |

**Free stock photo sources:** [Unsplash – construction](https://unsplash.com/s/photos/construction), [Pexels – construction](https://pexels.com/search/construction/)

---

## nonprofit.html

Folder: `assets/nonprofit/`

| Filename | Dimensions | Description |
|---|---|---|
| `hero.jpg` | 1920×1080 | Hero background — community event, group of volunteers, or families |
| `program-1.jpg` | 700×220 | Food pantry, volunteers distributing food |
| `program-2.jpg` | 700×220 | Kids in classroom, tutoring, or youth program |
| `program-3.jpg` | 700×220 | Community gathering, neighbors talking |
| `donate-photo.jpg` | 600×750 | Vertical impact photo — family, kids, or heartfelt moment |

**Free stock photo sources:** [Unsplash – volunteer](https://unsplash.com/s/photos/volunteer), [Pexels – community](https://pexels.com/search/community/)

---

## restaurant.html

Folder: `assets/restaurant/`

| Filename | Dimensions | Description |
|---|---|---|
| `hero.jpg` | 1920×1080 | Hero background — dining room ambiance or signature dish close-up |
| `interior.jpg` | 900×700 | Interior dining room, bar, or kitchen — for the "Our Story" section |
| `dish-1.jpg` | 200×200 | Square dish photo — appetizer or salad |
| `dish-2.jpg` | 200×200 | Square dish photo — main entrée |
| `dish-3.jpg` | 200×200 | Square dish photo — fish or protein |
| `dish-4.jpg` | 200×200 | Square dish photo — dessert |
| `gallery-1.jpg` | 400×500 | Atmosphere or detail shot |
| `gallery-2.jpg` | 400×500 | Plating close-up or bar shot |
| `gallery-3.jpg` | 400×500 | Dining room detail or candles |
| `gallery-4.jpg` | 400×500 | Chef, kitchen, or seasonal ingredient |

**Free stock photo sources:** [Unsplash – food](https://unsplash.com/s/photos/food), [Pexels – restaurant](https://pexels.com/search/restaurant/)

---

## salon.html

Folder: `assets/salon/`

| Filename | Dimensions | Description |
|---|---|---|
| `hero.jpg` | 900×1100 | Vertical portrait — stylist in studio, or studio interior |
| `work-1.jpg` | 600×900 | Vertical feature — hair result (color, cut, style) |
| `work-2.jpg` | 600×600 | Square — hair result |
| `work-3.jpg` | 600×600 | Square — hair result |
| `work-4.jpg` | 1200×520 | Wide — hair result or salon atmosphere |
| `work-5.jpg` | 600×600 | Square — hair result |
| `work-6.jpg` | 600×600 | Square — hair result |
| `headshot.jpg` | 600×800 | Vertical portrait of stylist — for About section |

**Free stock photo sources:** [Unsplash – hair salon](https://unsplash.com/s/photos/hair-salon), [Pexels – hairstyle](https://pexels.com/search/hairstyle/)

---

## Tips

- **File format:** JPG preferred for photos. Use PNG only for logos/graphics with transparency.
- **Compression:** Run photos through [Squoosh](https://squoosh.app) or [TinyPNG](https://tinypng.com) before uploading — aim for under 300KB per photo.
- **Object-fit:** All photo slots use `object-fit: cover` so any reasonable aspect ratio will work. The dimensions above are just the ideal targets.
- **Alt text:** Add descriptive alt text to each `<img>` tag for SEO and accessibility.
