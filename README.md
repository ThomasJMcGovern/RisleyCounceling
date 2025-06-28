# Risley Leskos Therapy Website

A professional therapy website for Risley Leskos, LMFT, offering individual, couples, and family therapy services in Los Angeles.

## Features

- Clean, modern design with a calming color palette
- Mobile-responsive layout
- SEO optimized with meta tags
- Fast loading static site
- Sticky navigation header
- Newsletter signup form
- Clean URLs enabled

## Deployment to Vercel

### Option 1: Deploy with Vercel CLI

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to link your project and deploy.

### Option 2: Deploy via GitHub

1. Push this code to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Sign in and click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect the settings and deploy

### Option 3: Deploy via Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Sign in and go to your dashboard
3. Drag and drop this folder onto the dashboard
4. Your site will be deployed instantly

## Project Structure

```
risley-leskos-therapy/
├── index.html          # Main website file
├── package.json        # Project metadata
├── vercel.json        # Vercel configuration
├── .gitignore         # Git ignore file
├── README.md          # This file
├── public/            # Public assets (if needed)
└── images/            # Image assets directory
```

## Customization

### Adding Images

Place your images in the `images/` directory and reference them in the HTML:
```html
<img src="/images/your-image.jpg" alt="Description">
```

### Updating Content

Edit the `index.html` file to update:
- Text content
- Contact information
- Services offered
- Navigation links

### Styling

All styles are currently embedded in the `index.html` file. To modify:
- Colors: Update the color values in the CSS
- Fonts: Change the font-family in the body selector
- Layout: Adjust grid and flexbox properties

## Environment Variables

No environment variables are required for this static site.

## Domain Setup

After deployment, you can add a custom domain in the Vercel dashboard:
1. Go to your project settings
2. Navigate to "Domains"
3. Add your custom domain
4. Follow the DNS configuration instructions

## Support

For deployment issues, refer to [Vercel's documentation](https://vercel.com/docs).

## License

© 2024 Risley Leskos Therapy. All rights reserved.