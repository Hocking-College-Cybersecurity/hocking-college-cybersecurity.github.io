# Contributing & Student instructions

Students:
- Use the program portfolio template (provided by the instructor) to create your portfolio repository.
- Add the repository topic: `cyber-portfolio` (Repository → Settings → Topics). This allows the program site to list your portfolio automatically.
- Keep your portfolio repo public if you want it listed on the program site. If you need it private for FERPA or other reasons, contact the Program Director to arrange a private listing or a sanitized excerpt.
- For each class assignment, add a markdown file under `deliverables/` following the provided deliverable template. This ensures your work is discoverable and presented uniformly to employers.

Instructors / Admins:
- The aggregator action runs daily and updates `_data/students.yml`. You can also run it manually from the Actions tab.
- If you need to aggregate private repos, create a minimal-scope PAT and store it in repository secrets; update the workflow to use that token.

Privacy:
- Obtain signed FERPA consent before publishing names or other personally-identifiable information.