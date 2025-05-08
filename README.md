# Self Cast Studios Website

This repository contains the client-facing website for Self Cast Studios, a podcast production company. The website is built with modern web technologies and connects to the Self Cast Studios CMS for content management.

## Quick Start Guide

To start the website locally:

```bash
cd C:\Users\digit\CascadeProjects\5-7-25-selfcast-website
npm install
npm run dev
```

This will start the development server on port 3000:
- Website: http://localhost:3000

## Project Structure

- `pages/` - Website pages (Home, About, Blog, Projects, Contact)
- `components/` - Reusable UI components
- `public/` - Static assets (images, fonts, etc.)
- `styles/` - CSS and styling files
- `lib/` - Utility functions and API helpers
- `api/` - API routes for connecting to the CMS

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Dynamic Content**: Content managed through the Self Cast Studios CMS
- **Blog System**: Displays blog posts from the CMS
- **Project Showcase**: Portfolio of podcast production projects
- **Contact Form**: Integrated form that submits to the CMS
- **Social Media Integration**: Displays social media content from various platforms

## CMS Integration

The website connects to the Self Cast Studios CMS API to fetch content for:
- Page content (Home, About, Blog, Projects, Contact)
- Global components (Header, Footer, Branding)
- Blog posts and articles
- Project portfolios
- Social media content

## Technology Stack

- **Frontend**: Next.js with React
- **Styling**: CSS Modules / Tailwind CSS
- **Data Fetching**: Fetch API / SWR
- **Deployment**: Vercel / Netlify

## Customization

The website's appearance is controlled by the Self Cast Studios CMS, which allows clients to customize:
- Brand elements (Logo, site title, tagline, primary color)
- Page content (Text, images, and settings for each page)
- Navigation (Custom labels and page visibility in the header)
- Footer (Contact information, social links, and copyright text)

## Development Workflow

1. Make changes to the website code
2. Test locally using `npm run dev`
3. Push changes to GitHub
4. Deploy to production using Vercel/Netlify
