# talk – Web Analytics Blog

A static blog website built to demonstrate web analytics implementation using Google Analytics, deployed via GitHub Pages.

## 🔗 Live Demo
[https://nix0123.github.io/web-analytics-blog/](https://nix0123.github.io/web-analytics-blog/)

## 📌 About
talk is a blog website developed as part of a mini project for the subject of Web Analytics. The project covers the full pipeline — from website creation and deployment to analytics integration, engagement tracking, conversion goals, and SEO optimization.

## 🎯 Objectives
- Deploy a static blog website using GitHub Pages
- Integrate Google Analytics (GA4) for traffic and behavior tracking
- Monitor real-time user activity via the Analytics dashboard
- Analyze engagement metrics: sessions, page views, bounce rate, engagement time
- Implement goal/conversion tracking using custom events
- Apply basic SEO techniques for improved search visibility

## 🛠️ Tech Stack
- HTML5, CSS3, JavaScript
- Bootstrap (Clean Blog Theme)
- Google Analytics 4 (gtag.js)
- GitHub Pages (Hosting)

## 📋 Implementation Steps

### 1. Website Creation
Built using a Bootstrap-based Clean Blog template from GitHub. Includes Home, About, Sample Post, and Contact pages with proper semantic HTML structure.

### 2. Deployment
Hosted on GitHub Pages by enabling Pages from repository settings with `main` branch and `/root` as source.

### 3. Google Analytics Integration
Created a GA4 property, generated a Measurement ID (`G-YCSD038YZF`), and embedded the `gtag.js` tracking script in the `<head>` of all pages.

### 4. Real-time Traffic Monitoring
Verified live tracking using the GA4 Realtime report. Simulated multiple users via incognito windows and different browser tabs.

### 5. User Engagement Analysis
Analyzed metrics under **Reports → Engagement → Overview**:
- Active users & new users
- Sessions and views per session
- Average engagement time
- Bounce rate

### 6. Conversion Tracking
Created a custom event `contact_visit` triggered when `page_location` contains `contact`. Marked it as a conversion in GA4 Admin → Events.

### 7. SEO Implementation
- Added `<meta>` tags: title, description, keywords, author
- Used semantic heading tags (H1–H3)
- Added `alt` attributes to images
- Created `sitemap.xml` and `robots.txt`

## 📊 Sample Events Tracked
| Event Name       | Count |
|------------------|-------|
| page_view        | 5     |
| user_engagement  | 3     |
| first_visit      | 2     |
| scroll           | 2     |
| session_start    | 2     |

## ✅ Results
- Website successfully deployed and publicly accessible
- GA4 tracking verified via Realtime and Engagement reports
- Conversion event (`contact_visit`) recorded and confirmed
- SEO meta tags and sitemap implemented

## 👤 Author
**SAC**  
+91-9878770515 | SAC.pvt@gmail.com
