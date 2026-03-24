# Cate Sandstrom - Website

Welcome to your new website! This is a clean, professional site built with simple HTML, CSS, and JavaScript. You own all the code, and it's designed to be easy to update.

## 🎯 What You Have

- **Complete website** with all your pages
- **Mobile-responsive design** - looks great on phones, tablets, and desktops  
- **Clean, minimal aesthetic** - light grey background, elegant serif fonts
- **Fast loading** - no bloat, just clean code
- **Easy to edit** - clear comments show you exactly where to make changes

## 📁 File Structure

```
catesandstrom-website/
├── index.html          # Homepage
├── about.html          # About page
├── music.html          # Music/videos page
├── duet.html           # Fiddle Duet page
├── workshop.html       # Tune Workshop page
├── calendar.html       # Calendar/events page
├── contact.html        # Contact form page
├── now.html            # What I'm Doing Now page
├── blog.html           # Blog page (hidden from nav)
├── consulting.html     # Consulting page (hidden from nav)
├── css/
│   └── style.css       # All your styles
├── js/
│   └── main.js         # Mobile menu functionality
└── images/             # Put all your photos here
    └── PLACEHOLDER-INFO.txt
```

## 🚀 Quick Start Guide

### Step 1: Set Up GitHub Account (5 minutes)

1. Go to [github.com](https://github.com)
2. Click "Sign up" 
3. Create a free account
4. Verify your email

### Step 2: Create Your Repository (3 minutes)

1. Once logged in, click the "+" in top right corner
2. Select "New repository"
3. Name it: **`catesandstrom.github.io`** (exactly this - it's important!)
4. Set to "Public"
5. Click "Create repository"

### Step 3: Upload Your Website Files (5 minutes)

1. On your new repository page, click "uploading an existing file"
2. Drag ALL the files and folders from your website folder
3. Add commit message: "Initial website upload"
4. Click "Commit changes"

### Step 4: Enable GitHub Pages (2 minutes)

1. In your repository, click "Settings" (top right)
2. Scroll down and click "Pages" (left sidebar)
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 2-3 minutes - your site will be live at `https://catesandstrom.github.io`

### Step 5: Connect Your Domain (10 minutes)

**Where you bought your domain (Wix, GoDaddy, etc.):**

1. Log into your domain provider
2. Find "DNS Settings" or "Domain Management"
3. Add these DNS records:

**Record Type: CNAME**
- Host/Name: `www`
- Value/Points to: `catesandstrom.github.io`

**Record Type: A** (add ALL four of these)
- Host/Name: `@` or leave blank
- Value/Points to:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`

4. Save changes
5. Back in GitHub Pages settings, add custom domain: `catesandstrom.com`
6. Check "Enforce HTTPS" (after domain verifies - may take 24 hours)

**Done!** Your site will be live at catesandstrom.com within 24-48 hours.

## ✏️ How to Update Your Website

### Adding/Changing Photos

1. Prepare your photos:
   - Resize to recommended dimensions (see `images/PLACEHOLDER-INFO.txt`)
   - Compress them (use [TinyPNG.com](https://tinypng.com))
   - Name them exactly as specified

2. In GitHub:
   - Go to your repository
   - Click into `images` folder
   - Click "Add file" → "Upload files"
   - Drag your photos
   - Click "Commit changes"

### Editing Text

1. In GitHub, click on the file you want to edit (e.g., `about.html`)
2. Click the pencil icon (top right) to edit
3. Make your changes
4. Scroll down, add commit message: "Updated about page"
5. Click "Commit changes"

**Examples of common edits:**

**Change your bio on About page:**
Open `about.html`, find:
```html
<p>Cate Sandstrom is a Traditional Irish Fiddler...</p>
```
Replace with your new text.

**Add a new event to Calendar:**
Open `calendar.html`, find the event list, add:
```html
<li class="event-item">Saturday, March 15 - Your Event Name</li>
```

**Change homepage hero text:**
Open `index.html`, find:
```html
<h1>Cate Sandstrom</h1>
```

### Adding YouTube Videos

1. Get your YouTube video ID (the part after `watch?v=`)
   - Example: `https://www.youtube.com/watch?v=ABC123XYZ`
   - Video ID is: `ABC123XYZ`

2. Open the page where you want the video
3. Find the video embed code, replace `YOUR_VIDEO_ID` with your actual ID:
```html
<iframe src="https://www.youtube.com/embed/ABC123XYZ"
```

### Showing/Hiding Pages from Navigation

**To SHOW the blog page:**
Open any HTML file, find in the navigation:
```html
<!-- <li><a href="blog.html">Blog</a></li> -->
```
Remove the `<!--` and `-->` to make it:
```html
<li><a href="blog.html">Blog</a></li>
```

**To HIDE it again:**
Add the `<!--` and `-->` back.

## 📧 Setting Up Forms

### Contact Form & Newsletter Signup

Your forms currently use placeholder URLs. Here's how to activate them:

**Option 1: Formspree (Recommended - Easiest)**

1. Go to [formspree.io](https://formspree.io)
2. Sign up for free account
3. Create a new form
4. Copy your form ID (looks like: `YOUR_FORM_ID`)
5. In each HTML file with a form, replace:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
   with your actual form ID

**Free tier includes:**
- 50 submissions/month
- Email notifications
- Spam filtering

**Option 2: Your own email script**
If you're comfortable with PHP, you can create your own form handler.

## 📮 Newsletter Service Setup

When you're ready to set up a newsletter service:

**Recommended: Buttondown**
- Clean, simple interface
- Free for up to 100 subscribers
- Markdown-based (very Derek Sivers style)
- Sign up at [buttondown.email](https://buttondown.email)

**Alternative: MailerLite**
- Free for up to 1,000 subscribers
- More features (automation, templates)
- Sign up at [mailerlite.com](https://mailerlite.com)

**To integrate:**
1. Sign up for chosen service
2. Get your signup form code
3. Replace the newsletter form in your HTML files

## 🎨 Customizing Design

### Changing Colors

Open `css/style.css`, find this section at the top:
```css
:root {
    --bg-color: #f5f5f5;          /* Light grey background */
    --text-color: #333333;        /* Dark grey text */
    --heading-color: #1a1a1a;     /* Almost black headings */
    --link-color: #333333;        /* Link color */
    --link-hover: #666666;        /* Link hover color */
    --accent-color: #000000;      /* Black accent */
}
```

Change any hex color code to your preferred color.

### Changing Fonts

The site uses:
- **Playfair Display** for headings
- **Lora** for body text

To change fonts:
1. Find new fonts at [Google Fonts](https://fonts.google.com)
2. Replace the font link in the `<head>` section
3. Update font names in `css/style.css`

## 🔧 Troubleshooting

**Site not updating after I made changes?**
- Wait 1-2 minutes for GitHub to rebuild
- Try hard refresh: Ctrl+Shift+R (PC) or Cmd+Shift+R (Mac)
- Clear browser cache

**Images not showing?**
- Check file names match exactly (case-sensitive!)
- Make sure images are in the `images` folder
- File format should be .jpg, .png, or .gif

**Mobile menu not working?**
- Make sure `js/main.js` file uploaded correctly
- Check browser console for errors (F12 → Console tab)

**Domain not working?**
- DNS changes take 24-48 hours
- Double-check all DNS records are correct
- Make sure you enabled HTTPS in GitHub Pages settings

## 📱 Social Media Links

To add your social media links:

1. Open any HTML file
2. Find the footer section:
```html
<div class="footer-social">
    <a href="https://www.facebook.com/catesandstrommusic" target="_blank">
        <i class="fab fa-facebook"></i>
    </a>
    <!-- Add more links here -->
</div>
```

3. Add your other links:
```html
<a href="YOUR_INSTAGRAM_URL" target="_blank">
    <i class="fab fa-instagram"></i>
</a>
<a href="YOUR_YOUTUBE_URL" target="_blank">
    <i class="fab fa-youtube"></i>
</a>
```

## 🎯 Next Steps

1. **Add your photos** - See `images/PLACEHOLDER-INFO.txt` for list
2. **Set up Formspree** - Activate your contact form
3. **Add YouTube videos** - Update video IDs in HTML
4. **Test everything** - Click through all pages on mobile and desktop
5. **Set up newsletter** - When you're ready (Buttondown or MailerLite)

## 💡 Tips for Success

- **Make small changes** - Edit one thing at a time and test
- **Keep backups** - Download your site files regularly
- **Use GitHub Desktop** - For easier file management (optional but helpful)
- **Learn as you go** - HTML is easier than you think!

## 🆘 Need Help?

- **HTML/CSS Questions:** [W3Schools.com](https://w3schools.com)
- **GitHub Help:** [GitHub Docs](https://docs.github.com)
- **Font Awesome Icons:** [FontAwesome.com](https://fontawesome.com/icons)

## 📄 License

This is YOUR website. You own all the code. Do whatever you want with it!

---

**Remember:** You're in control now. No more Wix fees, no more limitations. This is YOUR site, built YOUR way. 🎻✨

If you want to make complex changes later, you can hire a web developer for a one-time fee instead of paying monthly subscriptions forever.

Welcome to owning your digital presence!
