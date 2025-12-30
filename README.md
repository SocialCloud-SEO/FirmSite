Law Firm Website (Static)
This repository contains the static website for a Texas personal injury law practice.
The site is intentionally minimal, fast, and mobile-first, with conversion focused on phone calls.
It is deployed as a static site using Netlify and does not require a backend or build step.

Purpose
The website serves three functions only:
Present the firm credibly and professionally
Encourage prospective clients to call 512-737-1111
Provide a minimal fallback contact form for callback requests
It is not an intake system, case evaluation tool, or client portal.

Technology
Plain HTML and CSS
No JavaScript frameworks
No backend services
Netlify static hosting (free tier)
Netlify Forms for basic contact submissions
This design prioritizes reliability, speed, and long-term maintainability.
Repository Structure
/
├── index.html        # One-page homepage
├── README.md         # This file
├── .gitignore        # Minimal ignore rules
└── assets/           # (Optional) images, icons, CSS if added later
No build artifacts are generated. All files in the repository are source-of-truth.

Deployment (Netlify)
Deployment is automatic once the repository is connected to Netlify.
Expected configuration:
Build command: none
Publish directory: / (repository root)
HTTPS: automatic via Netlify
To deploy manually:
Commit and push changes to the main branch
Netlify deploys automatically

Contact Form
The site includes a simple Netlify form used only to request a callback.
Form characteristics:
Short, non-invasive fields
No file uploads
No case evaluation logic
Clear disclaimer that no attorney-client relationship is formed
Submissions are treated as unprivileged inquiries until reviewed.

Legal and Ethics Notes
The website does not provide legal advice
No attorney-client relationship is formed by visiting the site or submitting the form
Visitors are instructed not to submit confidential or time-sensitive information
Calls may be answered by a live answering service when attorneys are unavailable
All copy is intentionally conservative and jurisdiction-specific.

Editing Content
To update the site:
Edit index.html
Commit changes
Push to the repository
No local server, build tools, or dependencies are required.

Design Principles
Mobile-first layout
Phone call as primary conversion action
Fast load time over visual complexity
Human, restrained tone
Avoidance of chatbots, popups, and automation gimmicks
This site is designed to age well and remain credible over time.

License

Content is proprietary to the law firm.
All rights reserved unless otherwise specified.
