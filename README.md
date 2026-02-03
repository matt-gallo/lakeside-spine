# Lakeside Spine & Injury Center

Official website for Lakeside Spine & Injury Center - Dr. Andrew Allen, Chiropractor in Wheat Ridge, Colorado.

## Website Overview

This is a modern, mobile-responsive website featuring:
- **Homepage** - Hero section, testimonials, conditions treated, and doctor bio
- **Services** - Interactive service tabs with detailed descriptions
- **FAQ** - Categorized frequently asked questions with accordion interface
- **Booking** - Calendar integration for appointments
- **Thank You** - Appointment confirmation page
- **Blog** - The Recovery Room (coming soon)

## Design Features

- Self-contained HTML pages with inline CSS
- Consistent navy (#1e293b) and gold (#fbbf24) color scheme
- Mobile-responsive with hamburger menus
- No external dependencies (except third-party widgets)
- Fast loading times
- SEO optimized

## Tech Stack

- HTML5
- CSS3 (inline styles)
- Vanilla JavaScript
- Node.js + Express (for Railway deployment)

## Local Development

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```

3. Open your browser to `http://localhost:3000`

## Deployment on Railway

This site is configured for easy deployment on Railway:

1. Push your code to GitHub (already done)
2. Go to [Railway](https://railway.app)
3. Click "New Project"
4. Select "Deploy from GitHub repo"
5. Choose the `lakeside-spine` repository
6. Railway will automatically detect the configuration and deploy

The site will be live at your Railway-provided URL.

## File Structure

```
├── index.html              # Homepage
├── services.html           # Services page
├── faq.html               # FAQ page
├── booking.html           # Booking calendar
├── thank-you.html         # Appointment confirmation
├── recovery-room.html     # Blog page
├── server.js              # Express server for Railway
├── package.json           # Node.js dependencies
├── railway.json           # Railway configuration
├── .gitignore             # Git ignore rules
├── archive/               # Legacy HTML files
│   └── legacy-html/       # Archived old pages
├── css/                   # Legacy CSS (not used)
├── images/                # Image assets
└── js/                    # Legacy JS (not used)
```

## Contact

**Lakeside Spine & Injury Center**
- **Phone**: (303) 351-0744
- **Email**: drallen@lakesidespineandinjury.com
- **Address**: 6073 W 44th Ave #101, Wheat Ridge, CO 80033

## License

© 2025 Lakeside Spine & Injury. All rights reserved.
