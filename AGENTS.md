# Magic Portfolio

A simple, clean, beginner-friendly portfolio template built with Next.js and Once UI.

## Tech Stack

- **Framework**: Next.js 16
- **UI Library**: Once UI + React 19
- **Styling**: Sass
- **Content**: MDX-based system for blog posts and projects
- **Language**: TypeScript
- **Node.js**: v18.17+ required

## Available Skills

| Skill | Description |
|-------|-------------|
| `build-and-deploy` | Build and deploy this Next.js portfolio application |

## Project Structure

```
src/
├── app/
│   ├── blog/posts/     # MDX blog posts
│   └── work/projects/  # MDX project pages
├── resources/
│   ├── once-ui.config.js  # Theme configuration
│   └── content.js         # Site content
public/
└── images/             # Static images
```

## Development Commands

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Start production server
npm start
```

## Configuration

1. **Theme & UI**: Edit `src/resources/once-ui.config.js`
2. **Content**: Edit `src/resources/content.js`
3. **Blog Posts**: Add `.mdx` files to `src/app/blog/posts/`
4. **Projects**: Add `.mdx` files to `src/app/work/projects/`

## Features

- Responsive design for all screen sizes
- Automatic SEO with Open Graph image generation
- Password protection for URLs
- About/CV page, Gallery, Blog, and Work sections
- Conditional section rendering based on content

## Documentation

Full documentation: [docs.once-ui.com](https://docs.once-ui.com/docs/magic-portfolio/quick-start)
