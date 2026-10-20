# Deadline Planner — CSE326 CA1
**Team:** Double Trible  
**Course:** CSE326  
**Project:** Student Deadline Planner

## Problem statement
Students track deadlines from several subjects using notebooks and messages. This application brings tasks into one planner so students can organize deadlines and monitor submission progress.

## Features
- Add, edit, and delete assignments/tasks
- Record subject, deadline, priority, submission status, and optional notes
- List view with search and status/priority filters
- Monthly calendar view
- Summary cards for total tasks, upcoming tasks, high-priority tasks, and submitted tasks
- Progress percentage based on submitted tasks
- Mark tasks submitted using the checkbox
- Export task data to CSV
- Responsive interface for laptop and mobile
- Browser localStorage persistence (data stays in the current browser/device)

## Technologies
- HTML5
- CSS3 (responsive layout)
- Vanilla JavaScript
- Browser localStorage and Blob API for CSV export

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Add a task using the form.

No package installation or backend server is required.

## Deploy with GitHub Pages
1. Create a GitHub repository (for example, `cse326-deadline-planner`).
2. Upload `index.html` and `README.md` to the repository's root.
3. Open **Settings → Pages** in the repository.
4. Choose deployment from the `main` branch and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site and copy the deployed URL into the CA1 submission sheet.

## Alternative deployment
You can import the repository into Vercel or Netlify and deploy it as a static site. Do not submit a link until it is live and tested.

## CA1 submission checklist
- [ ] Project title and team name are correct
- [ ] Both team members' registration numbers are included
- [ ] GitHub repository link works
- [ ] Deployed link opens without login
- [ ] Video presentation link works and includes all team members
- [ ] Test list/calendar views and all task actions before recording
- [ ] Each team member can explain their contribution and source code

## Team
- Bhanu Pratap Singh — 12620285
- Aryan Kumar — 12616957
- Team name: Double Trible

## Important note
Tasks are saved only in the browser/device where they were created. This project does not sync tasks between devices or users because it has no backend.
