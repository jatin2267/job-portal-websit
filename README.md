# Job Portal Website

> A multi-role job board and campus placement management web platform connecting job seekers, employers, and university placement cells.

---

## Features

- **Multi-Role User Experience**: Dedicated interfaces for Job Seekers (Students), Employers (Companies), and University Placement Officers (TPO).
- **Comprehensive Job Search & Discovery**:
  - Filter jobs by category, job type, salary range, and company.
  - Dedicated pages for browsing all jobs, latest openings, and saved/bookmarked jobs.
  - Detailed single job view with role requirements, responsibilities, and benefits.
- **Candidate Portal & Onboarding**:
  - Student registration and profile editing.
  - Centralized candidate dashboard tracking applications and interview stages.
  - Seamless "Apply Now" application submission interface.
- **Employer Recruitment Management**:
  - Company onboarding and profile management.
  - Job posting creation form with customizable requirements and salary ranges.
  - Job listing management dashboard to monitor, edit, and archive active vacancies.
  - Applicant tracking table and deep candidate inspection page.
- **Campus Placement Cell Integration**:
  - University placement officer dashboard monitoring campus placement drives.
  - Campus drive job management and student applicant oversight.
- **Informational & Trust Pages**:
  - Verified company directory and employer solutions pages.
  - About Us, Team, Partners, Testimonials/Reviews, and Contact Support with maps.
- **Responsive Layout**: Designed with clean Flexbox and Grid layouts optimized for desktop, tablet, and mobile viewports.

---

## Tech Stack

- **Markup**: HTML5
- **Styling**: CSS3 (custom CSS variables, responsive Flexbox & CSS Grid layouts)
- **Icons & Typography**: FontAwesome 6 CDN, Google Fonts (Arial / sans-serif stack)
- **Vector Graphics & Media**: SVG icons, AVIF/PNG optimized image assets

---

## Project Structure

```plaintext
job-portal-websit/
├── Assets/
│   ├── images/                        # Company logos, promotional banners, and category SVGs
│   └── img-about us/                  # About page illustrations, partner logos, and banners
├── about.html                         # Mission, platform stats, and company story
├── applicant-detail.html              # In-depth candidate review view with resume data
├── apply-now.html                     # Job application submission form
├── browse-jobs.html                   # Job browsing page with category & keyword filters
├── companies.html                     # Directory of hiring partner companies
├── company-dashboard.html             # Recruiter dashboard for job postings and candidate metrics
├── company-view-applicants.html       # Recruiter applicant review and status tracking view
├── contact-us.html                    # Inquiry form, location details, and support info
├── edit-profile.html                  # Candidate profile and skills management page
├── employers.html                     # Employer hiring solutions and feature highlights
├── index.html                         # Main landing page with hero banner, search, and featured roles
├── jobdetail.html                     # Primary single job listing and requirements view
├── jobs.html                          # Full job directory and search filter page
├── latest-jobs.html                   # Feed of recently published opportunities
├── login.html                         # Account authentication sign-in form
├── manage-jobs.html                   # Recruiter management panel for active and closed jobs
├── new-job-detail.html                # Alternative modern job description and benefits interface
├── partners.html                      # Academic and enterprise partnership showcase
├── placement-dashboard.html           # Campus placement officer dashboard with drive statistics
├── placement-manage-jobs.html         # Campus drive job listings management interface
├── placement-view-applicants.html     # Placement cell student interview status tracker
├── post-job.html                      # Job posting form with description, skills, and salary
├── register.html                      # Portal account registration hub
├── register-company.html              # Employer/company registration form
├── register-placement.html            # University training and placement cell registration
├── register-student.html              # Student and job seeker sign-up form
├── saved-jobs.html                    # Candidate bookmarked and saved job opportunities
├── student-dashboard.html             # Candidate application tracking and metrics portal
├── team.html                          # Platform team and leadership profile cards
├── view-all-reviews.html              # Candidate and recruiter testimonials page
├── Left (1).png                       # Navigation / banner UI graphic
├── shield.svg                         # Trust / verification SVG badge
├── student.svg                        # Candidate role vector illustration
├── Vector.svg                         # UI directional icon asset
├── TODO.md                            # Development notes and roadmap tracker
└── README.md                          # Project documentation
```

---

## How to Install and Run

This is a standalone frontend project requiring no backend servers or build steps.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jatin2267/job-portal-websit.git
   cd job-portal-websit
   ```

2. **Open in browser:**
   - Double-click `index.html` to open it in your browser of choice (Chrome, Edge, Firefox, Safari).
   - Alternatively, serve it via any local development server:
     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (npx)
     npx serve .
     ```
   - Navigate to `http://localhost:8000` in your web browser.

---

## Screenshots

> _Screenshots placeholder: Add UI previews of the homepage, candidate dashboard, and job listings here._

```markdown
![Homepage Preview](Assets/images/Banner.png)
```

---

## Author

- **Jatin** — [@jatin2267](https://github.com/jatin2267)
