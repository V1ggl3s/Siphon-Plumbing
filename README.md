# Siphon Plumbing — Website

Professional website for **Siphon Plumbing**, a certified plumbing business serving the Auckland region, operated by Amlesh Prasad.

## Pages

- **Home** — Hero section, services overview, why choose us, testimonials, FAQ, service area map, CTA
- **About** — Business background, operator bio, values, certifications
- **Services** — Detailed plumbing services with descriptions and CTAs
- **Contact** — Contact form (Web3Forms), phone, email, map
- **Gallery** — Photo gallery of completed work (add images to `/images/`)
- **Testimonials** — Customer reviews with Google Reviews integration

## Tech Stack

- HTML5, CSS3, Vanilla JavaScript
- Google Fonts (Inter)
- Font Awesome 6 icons
- Web3Forms for contact form email delivery

## Setup

1. Clone the repository
2. Open `index.html` in a browser — no build step required

### Contact Form Email Setup

The contact form uses [Web3Forms](https://web3forms.com) (free, no backend needed):

1. Go to [web3forms.com](https://web3forms.com)
2. Enter the business email (`amleshdp@hotmail.com`) and get an access key
3. Open `contact.html` and replace `YOUR_WEB3FORMS_ACCESS_KEY` with the key

### Adding Gallery Images

1. Place images in the `/images/` folder
2. In `gallery.html` (and `index.html` gallery section), replace the placeholder `<div class="gallery-item__placeholder">` blocks with `<img>` tags:

```html
<div class="gallery-item">
  <img src="images/your-photo.jpg" alt="Description of work">
  <div class="gallery-item__overlay"><i class="fas fa-expand"></i></div>
</div>
```

## Deployment

This is a static site — deploy to any static hosting:

- **GitHub Pages** — Push to repo, enable Pages in Settings
- **Netlify** — Drag and drop the folder, or connect to GitHub
- **Vercel** — Import the repo
- **Cloudflare Pages** — Connect to GitHub

## Project Structure

```
Siphon Plumbing/
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page
├── gallery.html        # Gallery page
├── testimonials.html   # Testimonials page
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # All JavaScript
├── images/             # Image assets
└── README.md
```

## Contact

**Siphon Plumbing**
Phone: 021 230 2415
Email: amleshdp@hotmail.com
Area: Auckland, New Zealand
