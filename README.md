# ReCityX Lab Website

Static website for the ReCityX Lab (Urban Agility and Resilience Laboratory), University of Florida.
Hosted with GitHub Pages. Every page is a plain HTML file. There is no database or build step.

## Files

| File | Page |
|---|---|
| `index.html` | Home (director bio, research topics, openings) |
| `team.html` | Team (current members, alumni, past contributors) |
| `research.html` | Funded projects and related publications |
| `publications.html` | Full publication list |
| `teaching.html` | Courses and curriculum |
| `media.html` | News coverage, talks, recognition, media kit |
| `join.html` | Open positions and how to apply |
| `images/team/` | Headshots (portrait, about 600 x 720 px, under 500 KB) |
| `images/pubs/` | Optional graphical abstracts for the Publications page |
| `images/brand/` | Lab logos |

## How to edit

1. Open the file on GitHub and click the pencil icon (Edit).
2. Find the text with Ctrl+F (Cmd+F on Mac) and change it. Keep the surrounding `<tags>` as they are.
3. Click **Commit changes** and write a short note, such as "Add new PhD student".
4. The live site updates within a few minutes.

Every change is saved in the history. To undo one, open the file's **History** and restore an earlier version.

## Common updates

**Add a team member (team.html)**
1. Upload the photo to `images/team/firstname-lastname.jpg`.
2. In `team.html`, copy an existing `<div class="person">...</div>` block, paste it in the right section, and change the photo path, name, role, bio, quote and links.

**Move a member to alumni (team.html)**
Cut their `<div class="person">` block and paste it under "PhD and Postdoc Alumni". Update their role to the current position.

**Add a publication (publications.html)**
Publications are stored as a list near the bottom of the file, inside `const P=[ ... ]`. Copy one entry, paste it at the top of the list, and edit `y` (year), `t` (type), `v` (journal short name) and `c` (citation). Optional image: `images/pubs/<id>.jpg`.

**Add a news item (media.html)**
Copy an existing `<div class="card">` block in "In the News", or an `<li>` line under "UF and Institute Coverage", and edit the outlet, date, headline and link.

**Update openings (join.html and index.html)**
Edit the opening cards in `join.html` and the "Opportunities" line near the bottom of `index.html`.

## Rules

- Do not rename the HTML files. The menu links depend on these names.
- Keep image file names lowercase with hyphens and no spaces.
- Get consent before posting anyone's photo or bio.
- Contact: Dr. Yan Wang, yanw@ufl.edu
