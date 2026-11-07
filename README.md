# Pathway Navigator

A smart career and education pathway navigator for Miami Dade College students. Built for the MDC "Smart Career and Education Pathway Navigator" challenge.

## What it does
A student picks a career (or takes a 5-question interest quiz). The app builds a step-by-step roadmap that starts at Miami Dade College and runs through transfer, certifications, internships and licensing.

- **Personalized:** full-time or part-time, start term, and credits already earned (AP, dual enrollment, transfer). Every step gets real term dates and an estimated finish.
- **Actionable:** each step lists where it happens, first tasks, and a link to the right institution.
- **Trackable:** mark milestones done, see progress and the next best action. Progress is saved in the browser.
- **Shareable:** copy the roadmap as text or copy a link straight to a career.

Demo careers: Architect, Mechanical Engineer, Chef, Cybersecurity Specialist, IT Consultant.

## How it works
- Single-file, dependency-free web app (`index.html`): HTML, CSS and vanilla JavaScript.
- Career pathways are data (`CAREERS` in the script). Adding a career means adding one object.
- Timeline math: 60-credit associate degree; 15 credits per full-time and 9 per part-time semester; Spring/Fall terms.
- Hash routing: `#quiz`, `#my-plan`, and one route per career (`#arch`, `#mech`, `#chef`, `#cyber`, `#itc`).

## Why it matters
Clear pathways mean fewer wasted credits and semesters, lower cost, and the guidance first-generation and working students often miss. Advisors spend their time on real decisions.

## Run locally
Open `index.html` in any browser. No build step.

## Deploy
Static site. On Netlify, publish directory is the repo root (see `netlify.toml`).

## Note
Program names, transfer partners and timelines are planning estimates for the prototype. Confirm with the MDC catalog and an advisor.
