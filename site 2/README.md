# Petite Orangerie — Website

Landing page for Petite Orangerie, a French-inspired glacerie & pâtisserie in Salt Lake City.

## Setup

### 1. Add your logo
Place your logo image in the `images/` folder as `logo.png`. This should be the watercolor orange branch logo with transparent or cream background. Recommended size: at least 400px wide.

### 2. Set up email form
Open `index.html` and find the `<form>` tag in the signup section. Replace `YOUR_FORM_ID` with your actual Formspree form ID:
- Go to [formspree.io](https://formspree.io)
- Create a free account
- Create a new form
- Copy the form ID (the part after `/f/`)
- Replace `YOUR_FORM_ID` in the action URL

### 3. Update social links
In the footer, update the Instagram and TikTok URLs to your actual handles.

### 4. Deploy to GitHub Pages
1. Create a new repository on GitHub
2. Push these files to the `main` branch
3. Go to Settings → Pages → Source: Deploy from branch → Branch: main → Save
4. Your site will be live at `https://yourusername.github.io/repo-name`

### 5. Connect your domain (Namecheap)
1. In GitHub repo Settings → Pages, enter your custom domain (e.g. `petiteorangerie.com`)
2. In Namecheap → Domain List → Manage → Advanced DNS, add:
   - A Record → Host: `@` → Value: `185.199.108.153`
   - A Record → Host: `@` → Value: `185.199.109.153`
   - A Record → Host: `@` → Value: `185.199.110.153`
   - A Record → Host: `@` → Value: `185.199.111.153`
   - CNAME Record → Host: `www` → Value: `yourusername.github.io`
3. Check "Enforce HTTPS" in GitHub Pages settings
4. Wait 10-30 minutes for DNS propagation

## File Structure
```
/
├── index.html          ← Main page
├── style.css           ← Styles
├── images/
│   └── logo.png        ← Your logo (add this)
├── CNAME               ← Your domain (GitHub creates this)
└── README.md           ← This file
```

## Brand Colors
- Bleu Doux: `#adc1c4`
- Ombre: `#7a9a9e`
- Dark: `#3a5558`
- Crème: `#fdf6ec`
- Orange Vif: `#e8743b`
- Doré: `#f5c56c`
- Green: `#2c891c`
