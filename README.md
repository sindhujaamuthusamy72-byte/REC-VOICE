# 🗣️ REC Voice

An anonymous feedback platform where students can report issues with
**teaching staff** or **college management** — without attaching a single
piece of personal information. No login, no name field, no tracking.

![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

## 📖 About

A lot of genuine problems on campus — biased grading, favoritism, unsafe
hostel conditions, unfair fee practices — go unreported because students
fear being singled out. **REC Voice** removes that barrier: there's nothing
to identify who submitted an issue, because nothing identifying is ever asked
for in the first place.

Every submission is categorized, tagged by severity, tracked with a status
(Pending / Under Review / Resolved), and can be upvoted by other students who
face the same problem — so the most common issues surface naturally.

> **Note:** This is a static front-end project (no backend/database). Submitted
> entries and "Me Too" counts are for demonstration only and reset on page
> refresh.

## ✨ Features

- 🔒 **True anonymity** — zero personal fields anywhere on the form
- 🗂️ **Categorized reporting** — Teaching & Staff vs. Management & Administration
- 🏷️ **Severity levels & tags** — Minor / Moderate / Serious, with issue tags like Facilities, Safety, Academic
- 🔎 **Live filtering & search** — filter the issue table by category, status, or severity, and search by keyword — all in real time with vanilla JS
- 👍 **"Me Too" upvoting** — surface the issues affecting the most students
- 📋 **Posting guidelines page** — keeps submissions factual and non-identifying
- 📱 **Responsive design** — works cleanly on mobile and desktop

## 🛠️ Tech Stack

| Layer | Tool |
|-------|------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, flexbox, responsive layout) |
| Interactivity | Vanilla JavaScript (DOM filtering, event handling) |
| Fonts | Google Fonts — Poppins & Inter |

## 📂 Project Structure

```
rec-voice/
├── index.html        # Home — intro, stats, how it works
├── submit.html        # Anonymous feedback submission form
├── browse.html        # Browse issues with live filter + search + upvote
├── guidelines.html    # Posting guidelines & status definitions
├── style.css           # Shared stylesheet for all pages
└── README.md
```

##  Getting Started

No installation or build tools required.

1. Clone the repo
   ```bash
   git clone https://github.com/your-username/rec-voice.git
   cd rec-voice
   ```
2. Open `index.html` directly in your browser, **or** use the
   [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   VS Code extension for auto-reload while editing.

## 🖱️ Usage

1. Go to **Submit Feedback** → pick a category, department, severity, and tags → describe the issue → submit
2. Go to **Browse Issues** → filter by category/status/severity or search by keyword → click **👍 Me Too** on any issue you've also faced
3. Check **Guidelines** for what makes a good, factual, non-identifying submission

## 🔭 Future Improvements

- [ ] Persist submissions with a real backend (Node/Express + database) instead of static demo data
- [ ] Add a modal with full issue details on row click
- [ ] Add a "Most Upvoted" sort option
- [ ] Admin view for the student council to update issue status
- [ ] Email digest of newly submitted issues (still anonymous to viewers)

## 🙋 Author

**Sindhu**
First-year student project — built to practice HTML forms, tables, and
JavaScript DOM manipulation with a real, useful idea.

## 📄 License

Open source and free to use for learning purposes.
