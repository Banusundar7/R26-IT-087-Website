<div align="center">

<img src="assets/images/logo.svg" alt="PomeGuard logo" width="96" />

# PomeGuard

### An AI-Based Intelligent Pomegranate Farming System for Yield and Quality

**Research project website · SLIIT · Project ID `R26-IT-087`**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![No JavaScript](https://img.shields.io/badge/JavaScript-none-008037?style=flat)
![Responsive](https://img.shields.io/badge/Responsive-mobile%20%7C%20tablet%20%7C%20desktop-cc1521?style=flat)

</div>

---

## About the project

Pomegranate farmers in Sri Lanka often make decisions without clear information. They
guess soil needs, notice diseases late, judge ripeness by eye and grade fruit by hand.
**PomeGuard** combines IoT sensors and AI in a single Flutter mobile app that supports
the farmer from soil to harvest.

| # | Component | Member |
|---|-----------|--------|
| 01 | 🌱 Growth Stage Detection & Harvest Prediction | V. Thishoharini |
| 02 | 🦠 Disease Detection, Severity & Treatment | S. Banuja |
| 03 | 🍎 Fruit Quality Grading & Waste Utilization | A. Sowmiya |
| 04 | 💧 Fertilizer Recommendation & Irrigation Prediction | T. Kobiram |

This repository holds the **project website** (HTML + CSS only). It presents the research
domain, milestones, documents, presentations and the team.

---

## Website sections

| Section | Menu link | What it shows |
|---------|-----------|---------------|
| **Home** | `#home` | Project title, ID and a short introduction |
| **Domain** | `#domain` | Literature survey, research gap, problem, objectives, methodology, the 4 core components and technologies used |
| **Milestones** | `#milestones` | Timeline from Topic Assessment to the Final Viva |
| **Documents** | `#documents` | Project management, proposal and final documents |
| **Presentations** | `#presentations` | Proposal, Progress 1, Progress 2 and Final presentations |
| **About Us** | `#about` | Supervisors and group members |
| **Contact Us** | `#contact` | Email, phone, location and a message form |

---

## Folder structure

```
website/
├── index.html              ← the whole website (start page)
├── README.md               ← this file
├── css/
│   └── style.css           ← all styling (colours, fonts, layout, mobile rules)
└── assets/
    ├── images/             ← logo, hero picture, component icons, team photos
    │   ├── logo.svg
    │   ├── hero.jpg                 (home background)
    │   ├── Growth.png  dis.png  fru.png  soil.png   (component icons)
    │   ├── Harini.jpeg  Banu.jpeg  Sowmi.jpeg  Ram.jpeg   (members)
    │   └── supervisor.jpeg  co-supervisor.jpeg
    ├── documents/          ← optional local PDFs
    └── slides/             ← optional local PDF / PPTX slides
```

> Most documents and slides are linked from **Google Drive / Google Docs**, so the
> `documents/` and `slides/` folders can stay empty. That keeps the upload small.

---

## How to view it

No installation or build step is needed.

1. Download or clone the folder.
2. Open **`index.html`** in any browser (Chrome, Edge, Firefox, Safari).

Or run a small local server from the folder:

```bash
python -m http.server 8000
# then open http://localhost:8000
```

---

## How to edit

### 1. Colours and fonts
Everything is in **one place** at the top of `css/style.css` (section *1. COMMON SETTINGS*).
Change a value there and the whole site updates.

| Variable | Use | Value |
|----------|-----|-------|
| `--red` | buttons, tags, links | `#cc1521` |
| `--green` | headings, icons | `#008037` |
| `--green-dark` | contact section, card backs | `#09591e` |
| `--footer-bg` | footer | `#18401c` |
| `--serif` / `--sans` | headings / body text | Fraunces / Inter |

### 2. Team photos
Replace the files in `assets/images/` and keep the **same names**
(e.g. `Banu.jpeg`), or change the `src="..."` in `index.html`.
Square photos (about 400 × 400 px, under 200 KB) look best.

### 3. Names, IDs and emails
Search `index.html` for the IT number (e.g. `IT22549440`) or the person's name and edit
the text next to it.

### 4. Documents and presentations
Each item is a link card. To add or replace one:

- **Google Drive file:** set *Share → Anyone with the link → Viewer*, then paste the link.
  - View: `https://drive.google.com/file/d/FILE_ID/view`
  - Download: `https://drive.google.com/uc?export=download&id=FILE_ID`
- **Local file:** copy it into `assets/documents/` or `assets/slides/` and use
  `href="assets/documents/File_Name.pdf"`.
- **Pending item:** keep it as `<div class="doc is-pending">`. When the file is ready,
  change it to `<a class="doc" href="...">`.

### 5. Milestones
Edit the dates, descriptions and marks in the `#milestones` section to match the
module's official marking scheme.

### 6. Contact details
Update the phone number, group email and supervisor emails in the `#contact` and
`#about` sections.

---

## Before uploading: checklist

- [ ] Supervisor emails replaced (search for `supervisor@sliit.lk` and `cosupervisor@sliit.lk`)
- [ ] All Google Drive links open for *Anyone with the link*
- [ ] `hero.jpg` and all team photos are present
- [ ] Photos compressed (JPG, about 100–200 KB each)
- [ ] Whole folder **under 20 MB** (course limit)
- [ ] Tested on a phone (menu button and layout)
- [ ] Folder uploaded with the **same structure**; `index.html` is the start page

---

## Technologies

**Website:** HTML5 · CSS3 (Flexbox, Grid, CSS-only mobile menu and flip cards) · Google Fonts

**Research system:** Flutter · TensorFlow / TensorFlow Lite · Keras · PyTorch (YOLO) ·
OpenCV · Python · Flask · Firebase · Google Colab · ESP32 IoT sensor · Git & GitHub

---

## The team

**Supervisors**
- Ms. Shashika Lokuliyana, *Project Supervisor*
- Mr. Samadhi Rathnayake, *Co-Supervisor*

**Group members**

| Name | Student ID | Email |
|------|-----------|-------|
| Thishoharini V | IT22281296 | it22281296@my.sliit.lk |
| Banuja S | IT22188304 | it22188304@my.sliit.lk |
| Sowmiya A | IT22549440 | it22549440@my.sliit.lk |
| Kobiram T | IT22245656 | it22245656@my.sliit.lk |

📧 Group email: **pomegranatefruit590@gmail.com** · 📍 SLIIT, Malabe Campus

---

<div align="center">

© 2026 PomeGuard · R26-IT-087 · Sri Lanka Institute of Information Technology

</div>