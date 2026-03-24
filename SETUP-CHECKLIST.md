# Setup Checklist ✅

Use this checklist to get your site live!

## Before You Launch

- [ ] Add all your photos to the `images` folder
- [ ] Replace placeholder YouTube video IDs with your actual videos
- [ ] Update social media links in footer
- [ ] Sign up for Formspree and add your form ID
- [ ] Test contact form
- [ ] Test newsletter signup form
- [ ] Update calendar with your actual events
- [ ] Review all text on every page

## GitHub Setup

- [ ] Create GitHub account
- [ ] Create repository named `catesandstrom.github.io`
- [ ] Upload all website files
- [ ] Enable GitHub Pages in Settings
- [ ] Verify site works at `https://catesandstrom.github.io`

## Domain Connection

- [ ] Log into your domain provider (where you have catesandstrom.com)
- [ ] Add CNAME record: `www` → `catesandstrom.github.io`
- [ ] Add A records (all 4 IP addresses)
- [ ] In GitHub Pages settings, add custom domain: `catesandstrom.com`
- [ ] Wait 24-48 hours for DNS to propagate
- [ ] Enable HTTPS in GitHub Pages settings
- [ ] Test site at `catesandstrom.com`

## Optional (Set Up Later)

- [ ] Choose newsletter service (Buttondown or MailerLite)
- [ ] Set up newsletter signup integration
- [ ] Add blog posts if you want to show the blog page
- [ ] Update consulting page if you want to show it

## Quick Edits You'll Want to Know

### Show/Hide Blog from Navigation
Find this in any HTML file's `<nav>` section:
```html
<!-- <li><a href="blog.html">Blog</a></li> -->
```
Remove `<!--` and `-->` to show it.

### Show/Hide Consulting from Navigation
Same process:
```html
<!-- <li><a href="consulting.html">Consulting</a></li> -->
```

### Add an Event to Calendar
Open `calendar.html`, find the event list, add:
```html
<li class="event-item">Your Date - Your Event</li>
```

### Change Your Email
Search all files for `CateSandstromMusic@gmail.com` and replace.

### Add Social Media Links
In footer section of any HTML file:
```html
<a href="YOUR_URL" target="_blank"><i class="fab fa-instagram"></i></a>
```

## Testing Checklist

Before announcing your site, test:

- [ ] All navigation links work
- [ ] Site looks good on phone (use your phone to check!)
- [ ] Site looks good on tablet
- [ ] Site looks good on desktop
- [ ] Contact form sends you emails
- [ ] Newsletter form works
- [ ] All photos load correctly
- [ ] Videos play properly
- [ ] No broken links

## You're Done! 🎉

Your website is live, you own it, and you're saving money every month.

---

**Reminder:** Save this checklist and the README.md - they're your guides for updating the site!
