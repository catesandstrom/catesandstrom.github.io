# Setup Checklist

## Before Launch

- [ ] Add all 26 photos to `/images` folder
- [ ] Add `favicon.png` (512x512px)
- [ ] Update workshop dates if needed
- [ ] Test all navigation links
- [ ] Check mobile responsiveness

## Domain Setup

1. GitHub Settings → Pages → Custom domain: `catesandstrom.com`
2. In domain registrar, add:
   - A Records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - CNAME: `www` → `yourusername.github.io`
3. Wait 24-48 hours for DNS
4. Enable HTTPS in GitHub Pages settings

## Form Setup

Replace `YOUR_FORM_ID` in `contact.html` with your Formspree ID from formspree.io

## Updates

Edit HTML files directly. Commit to deploy.
