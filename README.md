# kais-siple-ass-date-changer

Got it 👍 — You don’t wanna waste time like I did.
Looking for a tool just to change the date? Here’s the easiest solution.
The simplest program ever. Only made to change the date on your image.
Please credit if shared or link the GitHub page.
---

# 🖼️ Modern Image Date Changer

A simple yet modern **GUI tool** to edit image dates and timestamps.
Built with **Python, Tkinter, and piexif**, this app allows you to:

* View and edit **EXIF metadata dates** (e.g., `DateTimeOriginal`, `DateTimeDigitized`)
* Change the **file’s modification timestamp**
* Save the updated image without losing the original
* Easily select a date using either manual text input or intuitive spinboxes

---

## ✨ Features

* 📂 Select and preview an image
* 📅 Edit dates via text entry (`2001:07:23 12:30:45`) or spinboxes for year/month/day/hour/minute/second
* 📝 Update EXIF tags:

  * `DateTimeOriginal`
  * `DateTimeDigitized`
  * `ImageIFD.DateTime`
* 🖥️ Update file modification time (filesystem date)
* 🔒 Original image remains untouched (saved as a copy)
* 🎨 Clean and modern Tkinter interface

---

## 🚀 Installation

Clone the repository and install requirements:

```bash
git clone https://github.com/Kaia-lcs/kais-siple-ass-date-changer
```

### Requirements

* Python 3.8+
* [pillow](https://pypi.org/project/pillow/)
* [piexif](https://pypi.org/project/piexif/)

---

## ▶️ Usage

Run the app with:

```bash
img date editor.exe
```

1. Click **Select Image**
2. Choose your desired date (entry or spinboxes)
3. Click **Save Changes**
4. A copy of the image will be saved with updated metadata and file timestamps

---

## 📷 Screenshots

*(Add your GUI screenshots here, e.g. in `/screenshots`)*

---

## ⚠️ Notes

* Supported formats: `JPG`, `JPEG`, `PNG`, `BMP`, `TIFF`, `GIF`, `WEBP`, `ICO`
* Not all image formats fully support EXIF metadata (e.g., PNG, GIF). In such cases, only the **file timestamp** will be updated.

---

## 🛠️ Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you’d like to improve.

---

## 📜 License

MIT License.

---

👉 Do you want me to also create the `requirements.txt` and `.gitignore` contents for you so the repo feels fully polished?
