# Manvendra Singh — Portfolio

A single-page personal portfolio styled like **Visual Studio Code**: explorer sidebar, tabs, editor area with syntax-highlighted “files,” activity bar, and status bar. All content and styling live in one static HTML file—no build step or framework.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/981e425c-7707-43bd-bc6d-27f682da265a" />


## Sections

| “File”            | Content                          |
| ----------------- | -------------------------------- |
| `about.md`        | Introduction                     |
| `experience.ts`   | Work experience                  |
| `projects.ts`     | Projects                         |
| `skills.json`     | Skills                           |
| `education.md`   | Education                        |
| `certificates.json` | Achievements & certificates   |
| `contact.json`    | Contact                          |
| `linkedin-posts.md` | LinkedIn posts / writing       |

## Tech

- Plain HTML, CSS, and JavaScript
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) (Google Fonts)
- [Font Awesome](https://fontawesome.com/) (CDN)

## Run locally

**Option A — open the file**

Double-click `index.html` or open it from your browser (File → Open).

**Option B — local server** (helps if you hit browser restrictions on `file://`):

```bash
npx --yes serve .
```

Then visit the URL printed in the terminal (often `http://localhost:3000`).

## Customize

Edit `index.html`: update copy in the editor pane, adjust `META` / data in the `<script>` block at the bottom, or change colors under the `:root` CSS variables.
