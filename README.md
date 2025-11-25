# Searchlight Capital - Data & Analytics Documentation

This repository contains the technical documentation for data projects across Searchlight Capital portfolio companies, built with [Mintlify](https://mintlify.com).

## Overview

This documentation site provides comprehensive guides for:

- **Analytics Stack**: Configuration guides and workflows for the modern analytics stack, including Snowflake, Cursor IDE, and Prime
- **Fiber Map**: Documentation for broadband infrastructure data covering the United States

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Local Development

1. Install the Mintlify CLI:

```bash
npm i -g mintlify
```

2. Navigate to the repository directory:

```bash
cd mintlify-docs
```

3. Start the local development server:

```bash
mintlify dev
```

4. Open your browser to `http://localhost:3000` to view the documentation

The site will automatically reload when you make changes to the documentation files.

## Project Structure

```
mintlify-docs/
├── analytics-stack/           # Analytics Stack documentation
│   ├── overview.mdx
│   ├── configuration/         # Configuration guides
│   │   ├── snowflake-mcp.mdx
│   │   ├── cursor.mdx
│   │   └── prime.mdx
│   ├── developer-workflow.mdx
│   └── business-user-workflow.mdx
├── fiber-map/                 # Fiber Map project documentation
│   ├── overview.mdx
│   ├── data-quality.mdx
│   ├── known-issues.mdx
│   └── faq.mdx
├── logo/                      # Brand assets
│   ├── dark.svg
│   └── light.svg
├── docs.json                  # Mintlify configuration
├── favicon.svg
└── index.mdx                  # Homepage
```

## Editing Documentation

All documentation files are written in MDX (Markdown with JSX support). To edit documentation:

1. Locate the relevant `.mdx` file in the appropriate folder
2. Make your changes using Markdown syntax
3. Preview changes locally using `mintlify dev`
4. Commit and push your changes

### Adding New Pages

1. Create a new `.mdx` file in the appropriate directory
2. Add frontmatter with `title` and `description`
3. Update `docs.json` to include the new page in the navigation structure

## Configuration

The `docs.json` file controls:

- Site metadata (name, colors, logo)
- Navigation structure (tabs, groups, pages)
- Footer content
- Theme settings

Refer to the [Mintlify documentation](https://mintlify.com/docs) for advanced configuration options.

## Deployment

This documentation site is automatically deployed when changes are pushed to the main branch. Mintlify handles the build and deployment process.

## Contributing

When contributing to this documentation:

1. Keep content clear and concise
2. Use proper Markdown formatting
3. Include code examples where appropriate
4. Test locally before committing
5. Follow the existing structure and style

## Support

For questions or issues related to:
- **Documentation content**: Contact the Searchlight Capital data team
- **Mintlify platform**: Visit [Mintlify's documentation](https://mintlify.com/docs)

## License

© 2025 Searchlight Capital. All rights reserved.

