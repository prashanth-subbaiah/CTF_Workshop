# CTF Workshop — GitHub Pages Static CTF (Beginner)

This repository contains beginner-friendly static CTF challenges across Web, Crypto, Forensics, and Linux.

IMPORTANT: `solutions.md` contains answers. **Remove it before making the site public** or keep the repository private for the event.

## How to host on GitHub Pages
1. Create a new GitHub repo (name: CTF-Workshop).
2. Upload all files from this folder (root of the repo).
3. In GitHub repo Settings → Pages, set Branch = `main` and Folder = `/ (root)`.
4. Save and wait ~1–2 minutes. Your site will be at `https://YOUR_USERNAME.github.io/CTF-Workshop/`.

## Test locally
From the project root run:

```bash
python3 -m http.server 8000
```
Then open http://localhost:8000

## Remove solutions.md before public hosting
- Locally: delete the file `solutions.md` and commit.
- Or keep the repo private and share the link only with participants.
