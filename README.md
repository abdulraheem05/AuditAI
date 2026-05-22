# AuditAI — Professional Website Auditor

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Cheerio](https://img.shields.io/badge/Cheerio-FFC107?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)


## Deployed URL
**[https://auditai-ar.vercel.app/](YOUR_DEPLOYED_URL_HERE)**

---

## What this is

**AuditAI** is an AI-powered website auditing tool that analyzes a live website and converts raw technical data into clear, actionable recommendations.

The project was built to help agencies, marketers, developers, and business owners quickly understand how well a website performs from a content, SEO, UX, accessibility, and conversion perspective.

Instead of only giving generic AI advice, AuditAI first extracts factual website metrics such as word count, heading structure, CTA count, internal/external links, image accessibility, and meta information. These structured metrics are then passed into an AI reasoning layer to generate practical recommendations based on real data.

The goal of this project was to build a fast, reliable, and deployable website auditor that works well in a serverless environment while still producing useful business-level insights.

---

## Key Features

- Analyze any public website URL
- Extract real website metrics from raw HTML
- Generate AI-powered website improvement suggestions
- Evaluate SEO structure using heading counts and meta information
- Identify CTA and conversion elements
- Measure internal and external link distribution
- Check image accessibility using missing `alt` text percentage
- Provide fast audit results optimized for serverless deployment
- Return structured recommendations in a clean, readable format

---

## What the Audit Measures

AuditAI extracts six major categories of factual website data before generating AI recommendations.

### 1. Content Health

The system calculates the total visible word count from the webpage while filtering out unnecessary code noise such as scripts, styles, and hidden technical elements.

This helps determine whether a page has enough meaningful content for users and search engines.

### 2. SEO Structure

AuditAI scans the website’s heading structure, including:

- H1 tags
- H2 tags
- H3 tags

It also includes fallback logic to detect common heading-like CSS classes when websites do not use proper semantic HTML tags.

### 3. Conversion Power

The tool counts conversion-focused elements such as:

- Buttons
- CTA links
- Primary action elements
- Elements using ARIA button roles

This helps evaluate whether the website is clearly guiding users toward meaningful actions.

### 4. Navigation Mapping

AuditAI separates links into:

- Internal links
- External links

This gives a quick understanding of the website’s navigation structure and how the page distributes users across internal pages or outside resources.

### 5. Accessibility Score

The system checks all images on the page and calculates the percentage of images missing `alt` text.

This helps identify basic accessibility and SEO issues related to image content.

### 6. Meta Information

AuditAI extracts important page metadata such as:

- Page title
- Meta description
- OpenGraph title
- OpenGraph description

These values are useful for SEO, search result previews, and social media sharing.
