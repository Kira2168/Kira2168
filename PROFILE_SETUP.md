# GitHub Profile Setup & Limitations

This document explains how the **Kira2168** profile README works and what you can (and cannot) control through repository content alone.

---

## How the Profile README works

GitHub displays the contents of `README.md` (from this repository, `Kira2168/Kira2168`) at the top of your profile page — https://github.com/Kira2168 — because **the repository name exactly matches your username**. That is the only special configuration required.

---

## What you CAN control via this repository

| What | How |
|---|---|
| The profile banner, bio, skills, projects, links | Edit `README.md` in this repo |
| The order of content visitors see | Rearrange sections in `README.md` |
| Hiding extra clutter | Keep `README.md` clean and minimal; avoid adding many badges/widgets |

---

## What you CANNOT fully control via repository code

GitHub's profile page always shows certain UI modules (contribution graph, repositories list, etc.) **below** your profile README. You cannot remove these entirely through repository content. However, you can reduce what appears using **GitHub account settings**:

### To reduce the contribution graph / activity section

1. Go to **https://github.com/settings/profile**
2. Scroll to the **Contributions & Activity** section (or **Public profile** area depending on your GitHub version).
3. Options available:
   - **"Include private contributions on my profile"** — turn this **off** so private-repo activity is not counted in your graph.
   - **"Show my contributions graph on my profile"** (if available in your plan) — toggle to hide the graph entirely.
4. Click **Save**.

### To make your profile private (hides everything from non-followers)

1. Go to **https://github.com/settings/profile**
2. Find **"Make profile private and hide activity"** and enable it.
3. This hides the contribution graph and activity feed from everyone except you.

> **Note:** GitHub's exact settings labels may change with UI updates. Look for anything related to *contributions*, *activity*, or *profile visibility* on your Settings → Profile page.

---

## Recommended workflow for customizing the README

1. Edit `README.md` in this repository.
2. Commit and push to the `main` branch.
3. Visit https://github.com/Kira2168 (while logged out or in a private window) to preview how it looks to others.
4. Repeat until satisfied.
