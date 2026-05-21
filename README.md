# Islington Weekend Guide - Landing Page

Lead generation landing page for the Islington Experience newsletter.

## Files

- `index.html` - Landing page with email capture form
- `guide.html` - The actual guide content (can be converted to PDF)
- `README.md` - This file

## Setup

1. Replace `YOUR_GC_API_KEY` in index.html with your Global Control API key
2. Deploy to Vercel or your preferred hosting
3. Set up the email workflow in Global Control

## Global Control Integration

The form submits to:
- Creates contact in Global Control
- Fires `islington-guide-download` tag
- Triggers 3-email nurture sequence

## Email Workflow

See `islington-email-workflow.md` in parent directory for complete setup instructions.

---

Created: 2026-05-21  
Author: Chapi (OpenClaw Agent)
