# MongoDB Minute Documentation

Documentation site for MongoDB Minute - a platform for creating, managing, and publishing 60-second MongoDB educational video content.

## Overview

This documentation provides comprehensive guides for:
- **Getting Started**: Setup and first episode creation
- **Content Creation**: Writing effective 60-second scripts
- **Workflow System**: Understanding the approval process
- **Admin Features**: Managing episodes and settings
- **API Reference**: Complete API documentation
- **Deployment**: Production deployment guide
- **Project Summary**: Architecture and technical details

## Quick Start

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run start
```

The site will be available at `http://localhost:3000` (or next available port).

### Build

Build for production:

```bash
npm run build
```

### Preview Production Build

Preview the production build locally:

```bash
npm run serve
```

## Documentation Structure

```
docs/
├── 10-intro.mdx              # Introduction to MongoDB Minute
├── 20-getting-started.mdx     # Getting started guide
├── 30-content-creation.mdx    # Content creation guide
├── 40-workflow-system.mdx     # Workflow & approval system
├── 50-admin-features.mdx      # Admin features documentation
├── 60-api-reference.mdx       # API reference
├── 70-deployment.mdx          # Deployment guide
├── 80-project-summary.mdx     # Project summary
└── summary.mdx                # Documentation summary
```

## Technology

This documentation site is built using [Docusaurus 3](https://docusaurus.io/), a modern static website generator.

### Features

- **MDX Support**: Write documentation with React components
- **Mermaid Diagrams**: Visual workflow representations
- **Search**: Full-text search with Lunr
- **Internationalization**: Multi-language support (English, Spanish)
- **MongoDB Branding**: Custom styling with MongoDB brand colors

## Configuration

Key configuration files:

- `docusaurus.config.js` - Main Docusaurus configuration
- `sidebars.js` - Sidebar navigation structure
- `src/css/custom.css` - Custom styling with MongoDB brand colors

## Contributing

To contribute to this documentation:

1. Make changes to the relevant `.mdx` files in the `docs/` directory
2. Test locally with `npm run start`
3. Submit a pull request for review

As `main` is protected, all changes must go through pull request review.

## Deployment

The documentation is configured for deployment to GitHub Pages. See the [Deployment Guide](/docs/70-deployment) for detailed instructions.

### Environment Variables

For local development, no environment variables are required. For production deployment, configure:

- Repository name
- Organization name
- Base URL

These are set in `docusaurus.config.js`.

## Resources

- [MongoDB Minute Application](https://your-app-url.com) - The main application
- [Docusaurus Documentation](https://docusaurus.io/docs) - Docusaurus docs
- [MongoDB Developer Center](https://www.mongodb.com/developer/) - MongoDB resources

## License

See LICENSE file for details.

---

**Last Updated**: December 4, 2025  
**Version**: 1.0
