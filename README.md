# 📁 Media Assets Repository

This repository is used to store and serve all shared media for SS Pro projects — including branding, client logos, vendor product images, and shared graphics.

All media here is hosted through **GitHub Pages** and can be accessed publicly at:
👉 [https://sspro-installs.github.io/media-assets/](https://sspro-installs.github.io/media-assets/)

---

## 🗂 Repository Structure

```
media-assets/
│
├── branding/           # SS Pro logos and company branding
├── clients/            # Client-specific logos and media
│   └── CRC/            # Example client (Calvary Revival Church)
│
├── shared/             # Reusable placeholders or generic media
│   └── placeholder.png
│
└── vendors/            # Manufacturer / vendor images
    ├── greengo/
    ├── beyerdynamic/
    └── nexo/           # Example new vendor
```

---

## 🧩 Adding New Media Files

You can upload new images **directly on GitHub.com** — no coding needed.  
All uploads automatically appear in the public gallery within ~1 minute.

### ▶️ To add new images to an existing folder:

1. Navigate to the correct folder (for example `vendors/greengo/` or `clients/CRC/`).
2. Click the **“Add file” → “Upload files”** button.
3. Drag your PNG or JPG files into the box.
4. Write a short commit message (e.g. *“Add new product images”*).
5. Click **Commit changes**.

✅ Your new images will automatically appear in the gallery.

---

## 🆕 To create a new vendor or client folder

> GitHub doesn’t let you “add a folder” directly, so you’ll make one using a small placeholder file.

1. Go to the parent folder where you want the new folder created.  
   Example: `vendors/`
2. Click **“Add file” → “Create new file”**.
3. In the filename box, type the new folder path followed by `/.gitkeep`.  
   Example:
   ```
   vendors/nexo/.gitkeep
   ```
4. Add a commit message like *“Create Nexo vendor folder”* and click **Commit new file**.
5. After the folder appears, go into it.
6. Click **“Add file → Upload files”** and drag your images in.

✅ That’s it — GitHub Pages will automatically detect your new folder and show it in the gallery.

---

## 🌐 Viewing Media

Visit the gallery any time:
🔗 [https://sspro-installs.github.io/media-assets/](https://sspro-installs.github.io/media-assets/)

The gallery automatically:
- Groups images by folder (`vendors`, `clients`, etc.)
- Generates thumbnails
- Expands / collapses folder groups for easier browsing

---

## 🧠 Best Practices

- Keep filenames **simple and consistent** (no spaces, use hyphens or underscores).
- Use **transparent PNGs** when possible for logos and product images.
- For versioning or variants, use suffixes like:
  ```
  GGO-INTERFACEX_v2.png
  SS-Pro-Logo-White-2025.png
  ```
- Only commit relevant media — avoid random exports or temp files.
- If a folder appears empty, ensure it includes at least a `.gitkeep` file.

---

## 🆘 Troubleshooting

| Problem | Likely Cause | Fix |
|----------|---------------|-----|
| Folder not showing in gallery | No `.gitkeep` file or no images inside | Add at least one image or `.gitkeep` |
| New images not visible online | GitHub Pages build delay | Wait 1–2 minutes and refresh |
| Image path not loading | Case sensitivity (e.g., `.PNG` vs `.png`) | Rename file to lowercase |

---

## 🧾 Credits

Maintained by the **SS Pro Installs** team.  
For repository or gallery updates, contact:  
📧 *web@sspro-installs.com*
