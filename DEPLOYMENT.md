# Islington Weekend Guide - Deployment Info

## Live URLs

**Landing Page:**
- https://islington-weekend-guide-open-claw-hf.vercel.app

**PDF Download:**
- https://github.com/horacef0/islington-weekend-guide/raw/main/The_Ultimate_Islington_Weekend_Guide.pdf

**GitHub Repo:**
- https://github.com/horacef0/islington-weekend-guide

## Status

✅ Landing page deployed  
✅ PDF lead magnet created (39KB)  
✅ Global Control API connected  
✅ Contact creation working  
✅ Tag created: `islington-guide-download` (ID: `6a0ec9419623b6235f9176dc`)  
⏳ SMTP configuration pending  
⏳ Email workflow pending (waiting on SMTP)  

## Global Control Setup

### Tags Created
- `islington-guide-download` (ID: `6a0ec9419623b6235f9176dc`) - Newsletter group

### Tags Needed for Full Workflow
- `islington-welcome-sent`
- `islington-day3-sent`
- `islington-day7-sent`

### API Key
Configured in `index.html`

## Next Steps

1. ✅ SMTP configuration in Global Control (SendGrid or SMTP.com)
2. Create remaining workflow tags
3. Build 3-email sequence with PDF attachment
4. Test full flow end-to-end
5. (Optional) Set up custom domain

## Email Workflow

See `../islington-email-workflow.md` for complete email sequence copy.

**Email 1:** Immediate delivery with PDF attachment  
**Email 2:** Day 3 - Hidden gem spotlight  
**Email 3:** Day 7 - Community building + engagement  

---

Last updated: 2026-05-21
