# 🌿 মহাসাফল্য ইউটোপিয়া | Mahasafol Utopia

## 100% Organic Food System - Bangladesh

A professional, multi-language, multi-page website for MS Utopia - an organization dedicated to making all food in Bangladesh organic, affordable, and accessible to every citizen.

---

## 📁 Project Structure

```
ms_utopia_website/
├── index.html          # Main homepage
├── css/
│   └── style.css       # All styles (responsive, professional)
├── js/
│   └── main.js         # Language switcher & interactivity
├── pages/              # Additional pages (future)
├── products/           # Product detail pages (future)
└── images/             # Product & branch images (add yours)
```

---

## 🚀 Features

### ✅ Implemented
- **Responsive Design** - Works on mobile, tablet, desktop
- **Language Switcher** - বাংলা / English toggle (top-right corner)
- **8 Divisional Offices** - All branches with Google Maps embed
- **Product Showcase** - No pricing, "Coming Soon" badges
- **Smooth Animations** - Scroll effects, hover animations
- **Professional UI** - Green/gold theme, clean typography
- **SEO Ready** - Meta tags, semantic HTML

### 🔮 Future Updates (Easy to Add)
- [ ] Product pricing (when ready)
- [ ] E-commerce functionality
- [ ] Online ordering system
- [ ] Payment gateway integration
- [ ] User accounts & login
- [ ] Admin dashboard
- [ ] Blog/News section

---

## 🛠️ How to Update Products

### Method 1: Direct HTML Edit
1. Open `index.html`
2. Find the `<!-- Store Section -->` comment
3. Copy any `.product-card` div and paste below
4. Update the icon, name, and description

### Method 2: JavaScript Dynamic Add
```javascript
// In browser console or new JS file
MS_Utopia.addProduct({
    id: 'new_product_5',
    name_en: 'Organic Ghee',
    name_bn: 'অর্গানিক ঘি',
    desc_en: 'Pure organic ghee from grass-fed cows',
    desc_bn: 'ঘাস খাওয়া গরুর বিশুদ্ধ অর্গানিক ঘি',
    icon: '🧈'
});
```

### Method 3: Ask AI
Simply tell me:
> "Add new product: [Name] - [Description]"

I'll generate the exact code to copy-paste!

---

## 🌍 Language System

All text is controlled by `js/main.js` in the `translations` object.

To add new text:
1. Add English version: `translations.en.your_key = "English Text"`
2. Add Bengali version: `translations.bn.your_key = "বাংলা টেক্সট"`
3. Add `data-key="your_key"` to HTML element

---

## 📱 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings → Pages
3. Select branch: `main`, folder: `/ (root)`
4. Your site is live at `https://yourusername.github.io/repo-name`

### Custom Domain
1. Add `CNAME` file with your domain
2. Update DNS settings
3. Enable HTTPS in GitHub settings

---

## 🎨 Color Scheme

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Green | `#2d5016` | Headers, buttons, navbar |
| Secondary Green | `#4a7c23` | Gradients, hover states |
| Accent Gold | `#c9a227` | Badges, highlights, CTAs |
| Light Green | `#e8f5e9` | Backgrounds, cards |

---

## 📞 Contact

For updates, support, or customizations:
- **Organization:** Mahasafol Utopia (MS Utopia)
- **Mission:** Organic food for all Bangladeshis

---

## 📄 License

© 2026 Mahasafol Utopia. All rights reserved.

---

**Built with ❤️ for a healthier Bangladesh** 🌱
