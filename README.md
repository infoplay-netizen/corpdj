# DJ iNFO - Professional DJ Website

A modern, multilingual website for DJ services specializing in weddings and corporate events. This repository contains two versions of the website:

1. **Main Website** - Located in the `/wedding` directory (featured version with pricing, booking, and reviews)
2. **Original Demo** - Located in the `/site` directory (simpler version)

The root `index.html` redirects to the main wedding website.

## Features

- 🎵 Modern dark theme with neon accents
- 🌍 Multilingual support (Ukrainian, Russian, English)
- 💰 Three pricing packages for different event types
- ✨ Animated UI with smooth transitions
- 📱 Fully responsive design
- 📞 Contact widget with Viber/Telegram integration
- 📝 Booking form with Web3Forms integration
- 🎉 Thank you page with confetti animation

## Project Structure

```
.
├── wedding/              # Main website files (featured version)
│   ├── index.html        # Homepage with all sections
│   ├── thank-you.html    # Thank you page after form submission
│   ├── css/
│   │   └── style.css     # All styles
│   └── js/
│       ├── script.js     # Main JavaScript functionality
│       └── i18n.js       # Internationalization
├── site/                 # Original demo website
│   ├── index.html        # Homepage
│   ├── css/
│   │   └── style.css     # Styles
│   └── js/
│       └── script.js     # JavaScript functionality
├── index.html            # Redirects to /wedding
├── package.json          # Project metadata and scripts
├── vercel.json           # Vercel deployment configuration
├── robots.txt            # SEO robots file
└── README.md             # This file
```

## Deployment to Vercel

1. Push this repository to GitHub
2. Sign up/log in to [Vercel](https://vercel.com)
3. Click "New Project"
4. Import this repository
5. Vercel will automatically detect the configuration and deploy

## Customization

- Update contact information in `wedding/index.html`
- Modify pricing packages in `wedding/index.html`
- Change Web3Forms API key in the booking form
- Update social media links in `wedding/index.html`

## License

This project is proprietary and belongs to DJ iNFO.