# PLUS HUB

The largest collection of free stuff on the internet!

Built with [VitePress](https://vitepress.dev/) - a static site generator powered by Vite and Vue.

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
plushub/
├── docs/                 # Documentation source files
│   ├── .vitepress/       # VitePress config and theme
│   │   ├── config.js     # Site configuration
│   │   └── theme/        # Custom theme
│   ├── index.md          # Homepage
│   └── ...               # Other markdown pages
├── public/               # Static assets (in docs/public)
│   └── assets/           # Images, icons, etc.
└── package.json          # Dependencies and scripts
```

## Development

The site runs on `http://localhost:5173` by default during development.

## Deployment

Build the site and deploy the `docs/.vitepress/dist` directory to any static hosting service:

- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

## License

This project is open source and available for use.

---

**Note**: This site does not host any files.
