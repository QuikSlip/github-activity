# Matt Duke -- GitHub Activity

Most of my development work happens in private and internal repositories under the [QuikSlip](https://github.com/QuikSlip) organization. GitHub's contribution graph does not count private org contributions unless the viewer is a member, so this page provides a transparent look at my actual engineering output.

## At a Glance

| Metric | Count |
|--------|-------|
| Merged Pull Requests | 85+ |
| Commits (across all repos) | 195+ |
| Active Repositories | 7 |
| Lines Changed (April 2026) | 5,000+ |

## Repositories

I am the founder and sole engineer of [QuikSlip](https://www.quikslip.com) -- a web-based parking management platform for apartment complexes in Texas. The platform spans 7 repositories covering the marketing site, admin portal, guest app, registration flow, email service, towing app, and development reports.

| Repository | Stack | Description |
|-----------|-------|-------------|
| **Property Management Portal** | Next.js, Tailwind, AWS Amplify | Admin dashboard for property managers -- tenants, guest passes, towing, violations, roster, daily reports |
| **Guest Application** | React Native, Expo, AWS Amplify | Mobile/web app for tenants and guests to obtain digital parking passes |
| **Registration Component** | React, MUI, AWS Cognito | 6-step onboarding wizard for new property managers |
| **Marketing Website** | Next.js, Tailwind, MUI | Public site at www.quikslip.com with SEO, schema markup, and demo request form |
| **Email Backend** | Node.js, Express, Nodemailer | Service for sending guest pass emails to tenants and visitors |
| **Towing App** | React Native, TypeScript | Mobile app for tow truck operators to manage jobs |
| **Weekly Reports** | Markdown | Automated weekly development reports with merged PRs and commit logs |

## Recent Merged Pull Requests

### Property Management Portal (35 merged PRs)

| PR | Title | Date |
|----|-------|------|
| #52 | Auto-expire guest passes after 24 hours | Apr 2026 |
| #51 | Comprehensive README | Apr 2026 |
| #50 | Persistent notifications with mark-as-read, dismiss, and clear | Apr 2026 |
| #49 | Daily activity report with email delivery | Apr 2026 |
| #48 | QuikSlip favicon for user menu + remove Tow button | Apr 2026 |
| #47 | Notification settings with emails + bell icon notifications | Apr 2026 |
| #46 | Remove subscription tab from settings | Apr 2026 |
| #45 | Mobile optimization across the portal | Apr 2026 |
| #44 | Pulsing glow on active lot indicator | Apr 2026 |
| #43 | Spacing between Tow and Delete buttons | Apr 2026 |
| #42 | Lots page with current lot display | Apr 2026 |
| #41 | Delete guest passes | Apr 2026 |
| #40 | Add search to guest passes page | Apr 2026 |
| #39 | Tow request from guest passes | Apr 2026 |
| #38 | Fix logo clipped and zoomed in | Apr 2026 |
| #36 | Role dropdown in property information settings | Apr 2026 |
| #35 | Violations page with dummy data + Texas address | Apr 2026 |
| #34 | Verify roster creation before closing modal | Apr 2026 |
| #33 | Remove unused settings tabs | Apr 2026 |
| #32 | Remove Security & Login tab from settings | Apr 2026 |
| #31 | Fix false error message on roster member creation | Apr 2026 |
| #30 | Redirect root route to dashboard | Apr 2026 |
| #29 | Build roster management with roles and VOIP call button | Apr 2026 |
| #28 | Manual guest pass creation and deletion | Apr 2026 |
| #27 | Build dashboard with property management stats | Apr 2026 |
| #26 | Add current lot display to management navigation | Apr 2026 |
| #25 | Remove Lot Pricing, Controller & Towing settings tabs | Apr 2026 |
| #24 | Delete tenant CRUD functionality | Apr 2026 |
| #23 | CSV bulk import for tenant onboarding | Apr 2026 |
| #21 | Change the logo | Apr 2026 |
| #20 | Remove console.log, fix JSX attributes, remove dead code | Apr 2026 |
| #19 | Replace hardcoded data with dynamic values | Apr 2026 |
| #18 | Fix OutlinedDropdown -- use props, bubble onChange | Apr 2026 |
| #17 | Wire settings save handlers, fix disabled logic | Apr 2026 |
| #16 | Update Cognito login fix | Apr 2026 |

### Marketing Website (34 merged PRs)

| PR | Title | Date |
|----|-------|------|
| #37 | Add citable content sections for SEO and AI search visibility | Apr 2026 |
| #36 | Fix footer H1 tags, privacy headings, copyright year, CSP header | Apr 2026 |
| #35 | Add llms.txt for AI search engine discoverability | Apr 2026 |
| #34 | Fix multiple H1 tags to single H1 per page | Apr 2026 |
| #33 | Add Open Graph and Twitter Card meta tags | Apr 2026 |
| #32 | Add image dimensions and hero preload for Core Web Vitals | Apr 2026 |
| #31 | Block /redirect from search indexing and update sitemap | Apr 2026 |
| #30 | Add JSON-LD schema markup (Organization, WebSite, FAQPage) | Apr 2026 |
| #29 | Add unique per-page titles, meta descriptions, and canonical tags | Apr 2026 |
| #27 | Add robots.txt with crawl directives and AI crawler rules | Apr 2026 |
| #24 | Add HTTP security headers and fix external link rel attributes | Apr 2026 |
| #21 | Remove Stripe link, replace with signup.quikslip.com | Apr 2026 |
| #20 | Fix small issues | Mar 2026 |
| #19 | Adding Stripe links to CTA | Mar 2026 |
| #16 | Make error message more descriptive | Mar 2026 |
| #15 | Fix phone form validation | Mar 2026 |
| #13 | Update Navbar | Mar 2026 |
| #11 | Add privacy policy | 2025 |
| #10 | Main site revisions 1.1 | 2025 |
| #9 | Add links and optimize desktop | 2025 |
| #8 | Improve SEO part 2 | 2025 |
| #7 | Optimize image compression for SEO | 2025 |
| #6 | Add better meta description | 2025 |
| #5 | Submit sitemap | 2025 |

### Registration Component (10 merged PRs)

| PR | Title | Date |
|----|-------|------|
| #23 | Responsive confirmation page redesign | Apr 2026 |
| #22 | Form UX consistency | Apr 2026 |
| #21 | Theme refinement and responsive fixes | Apr 2026 |
| #20 | Dead code cleanup | Apr 2026 |
| #19 | Fix step 4 and confirmation content | Apr 2026 |
| #18 | Fix complex step optional fields | Apr 2026 |
| #16 | Add license plate validation | Apr 2026 |
| #14 | Add car make/model autocomplete | Apr 2026 |
| #10 | Change redirect to Stripe payment | 2025 |
| #6 | Update parking fields to optional | 2025 |

### Guest Application (5 merged PRs)

| PR | Title | Date |
|----|-------|------|
| #17 | Car make/model autocomplete using NHTSA vPIC API | Apr 2026 |
| #16 | License plate validation across all forms | Apr 2026 |
| #15 | Optimize layout for mobile and desktop | Apr 2026 |
| #13 | Add Amplify auth and guest pass features | 2025 |
| #12 | Initial app setup | 2025 |

### Email Backend (1 merged PR)

| PR | Title | Date |
|----|-------|------|
| #1 | Created endpoint for sending email | 2025 |

## What I Work With

**Languages:** JavaScript, TypeScript, Python, SQL

**Frontend:** React, React Native, Next.js, Expo, Tailwind CSS, Material-UI

**Backend:** Node.js, Express, AWS Lambda, GraphQL (AppSync)

**Cloud:** AWS (Amplify, Cognito, DynamoDB, SES, API Gateway, Lambda, S3), Vercel

**Data:** DynamoDB, Google Sheets API, GraphQL

**Tools:** Git, GitHub Actions, Amplify CLI, Stripe

## About Me

Matt Duke -- Dallas, TX
Founder of [QuikSlip](https://www.quikslip.com) | Product @ Deloitte (MVP Award, top 10 out of 2,600)
USC -- Statistics, Physics, Math, Computer Science

[LinkedIn](https://www.linkedin.com/in/the-duke/) | [QuikSlip](https://www.quikslip.com)
