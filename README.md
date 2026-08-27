# Paul Omude — Personal Academic Website

[![Website Quality Check](https://github.com/omudepaul/omudepaul.github.io/actions/workflows/website-check.yml/badge.svg)](https://github.com/omudepaul/omudepaul.github.io/actions/workflows/website-check.yml)

This repository contains the source code for my personal academic and professional website.

🌐 **Live Website:**  
https://omudepaul.github.io

---

## About

I am a Ph.D. student in Computer Science at Oklahoma State University.

This website provides an overview of my academic background, professional experience, teaching activities, publications, technical skills, awards, professional memberships, curriculum vitae, and contact information.

---

## Website Sections

The website currently includes:

- Home
- About Me
- Education
- Professional Experience
- Teaching
- Selected Publications
- Technical Skills
- Awards & Honors
- Professional Memberships
- Curriculum Vitae
- Contact Information

---

## Technologies Used

The website is built using:

- HTML5
- CSS3
- JavaScript
- Responsive Web Design
- Git
- GitHub
- GitHub Pages
- GitHub Actions

No external front-end framework is required.

---

## Website Features

The website includes:

- Responsive desktop and mobile design
- Mobile navigation menu
- Accessible navigation and keyboard focus support
- Active navigation highlighting
- Professional SVG icons
- Curriculum Vitae viewing and download
- Protected public CV PDF
- Social media preview metadata
- Open Graph metadata
- Twitter/X preview metadata
- Schema.org structured data
- Google Analytics 4 integration
- Custom website interaction event tracking
- Google Search Console verification
- XML sitemap
- Robots.txt configuration
- Custom 404 page
- Privacy and analytics page
- Automated GitHub Actions quality checks

---

## GitHub Actions

The repository includes an automated **Website Quality Check** workflow.

The workflow runs whenever changes are pushed to the `main` branch or when a pull request targets the `main` branch.

The automated checks verify:

- Required website files are present
- Required image files are present
- HTML files can be validated
- The website repository remains ready for deployment

The workflow status is displayed at the top of this README.

---

## Analytics

Google Analytics 4 is used to understand general website usage and visitor interaction.

Examples of tracked interactions include:

- CV views
- CV downloads
- GitHub link clicks
- LinkedIn link clicks
- Email link clicks
- ACM link clicks
- Privacy page visits

Analytics information is used to better understand website usage and improve the visitor experience.

For additional information, see the website's Privacy & Analytics page:

https://omudepaul.github.io/privacy.html

---

## Professional Membership

I am a member of the:

**Association for Computing Machinery (ACM)**

https://www.acm.org/

---

## Repository Structure

```text
omudepaul.github.io/
│
├── .github/
│   └── workflows/
│       └── website-check.yml
│
├── images/
│   ├── profile.jpg
│   └── og-image.png
│
├── index.html
├── privacy.html
├── 404.html
├── cv.pdf
├── robots.txt
├── sitemap.xml
└── README.md
```

---

## Local Preview

To preview the website locally on Windows:

```cmd
cd C:\Users\omude\Documents\omudepaul.github.io
start index.html
```

---

## Updating the Website

After making changes to the website, review the repository status:

```cmd
git status
```

Add the updated files:

```cmd
git add .
```

Commit the changes:

```cmd
git commit -m "Update personal website"
```

Push the changes to GitHub:

```cmd
git push
```

GitHub Pages will automatically deploy the updated version.

The GitHub Actions workflow will also run automatically to perform the configured website quality checks.

---

## Deployment

The website is hosted using **GitHub Pages**.

The production website is available at:

https://omudepaul.github.io

The site is deployed from the `main` branch of this repository.

---

## Versioning

Stable versions of the website can be preserved using Git tags.

For example:

```cmd
git tag -a v1.0 -m "First complete version of personal academic website"
git push origin v1.0
```

Git tags make it possible to preserve important versions of the website and return to them later if necessary.

---

## Search Engine Optimization

The website includes several features designed to improve discoverability and search-engine indexing:

- Meta description
- Canonical URL
- Google Search Console verification
- `robots.txt`
- XML sitemap
- Open Graph metadata
- Twitter/X metadata
- Schema.org structured data
- Descriptive page titles

---

## Privacy

The website uses Google Analytics to measure general site usage and selected website interactions.

A dedicated privacy page is available at:

https://omudepaul.github.io/privacy.html

---

## Contact

**Paul Omude**

Ph.D. Student in Computer Science  
Oklahoma State University

**Email:**  
omudepaul@gmail.com

**LinkedIn:**  
https://www.linkedin.com/in/omudepaul

**GitHub:**  
https://github.com/omudepaul

**Website:**  
https://omudepaul.github.io

---

## License and Usage

This repository contains the source code and personal content for my academic and professional website.

Website content, personal information, curriculum vitae, photographs, and other personal materials may not be reproduced or redistributed without permission.

The underlying HTML, CSS, and JavaScript structure may be used for educational reference.

---

© Paul Omude. All Rights Reserved.