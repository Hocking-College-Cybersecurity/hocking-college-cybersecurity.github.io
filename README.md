# Cybersecurity Program — Hocking College (GitHub Pages site)

This repository is the GitHub Pages site for the Cybersecurity Program at Hocking College.

How it works:
- Students create portfolio repositories and add the `cyber-portfolio` topic.
- The aggregator GitHub Action finds those repos and updates `_data/students.yml`.
- The site reads `_data/students.yml` and displays portfolio cards on the home page.

What to do now:
1. Create a repository in the hocking-college-cybersecurity org named `hocking-college-cybersecurity.github.io`.
2. Add the files from this repo (copy/paste or push with git).
3. In repository Settings → Pages: select Branch `main` and folder `/ (root)` and save.
4. If you plan to list private student repos, configure a PAT and update the workflow to use it.

Contact:
Program Director: Norma DePriest — depriestn@hocking.edu
