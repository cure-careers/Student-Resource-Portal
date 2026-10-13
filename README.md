# CURE Student Resource Portal

Static website for The CURE Center for Ultrasound Research and Education, White Plains, NY.
No build step and no server code. Everything runs in the browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example `cure-student-portal`).
2. Upload the contents of this folder to the repository root. index.html must sit at the top level, next to the files, docs and physics folders. Keep the `.nojekyll` file.
3. In the repository, open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select the `main` branch and the `/ (root)` folder, and save.
4. After a minute or two the site is live at `https://<your-github-account>.github.io/cure-student-portal/`.
5. Optional: to use a CURE address such as `portal.cure.edu`, enter it under "Custom domain" on the same Pages screen and add the DNS record GitHub shows you at your domain provider.

## Updating content

* Syllabi: `files/syllabi/<CODE>.pdf` (for example `DMS100.pdf`)
* Lecture slides: `files/slides/`, listed in the `SLIDES` table in index.html
* Protocols: `files/protocols/`, listed in the `PROTOCOLS` table in index.html
* Staff contacts: the `PEOPLE` table in index.html
* Textbook collection: the `BOOKS` table in index.html
* Loan rules: `LOAN_DAYS` and `MAX_ACTIVE` near the top of the script in index.html

## Announcements

Closures, delayed openings and early dismissals come from the Google Sheet "CURE Alerts (Student Portal Announcements)". The sheet ID is set in `ALERTS_SHEET_ID` in index.html. The sheet must be shared as "Anyone with the link: Viewer".

## Notes

* On GitHub Pages, book requests go to the Registrar by email. The online reservation desk only works in the Claude hosted version.
* Documents open in the built in reader, but any file in a public repository can be reached directly by its address.
