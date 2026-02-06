# Evergreen Studio Dashboard

Production control center for managing video projects and creative workflows.

## Quick Start

This folder is configured for GitHub Pages deployment to `studio.evergreenmediadesign.com`.

### Files
- `CNAME` - Contains: `studio.evergreenmediadesign.com`
- `index.html` - Main landing page
- `README.md` - This file

### Deployment

1. Create a new GitHub repository: `evergreen-studio`
2. Copy this folder contents to the repo root
3. Push to GitHub
4. Go to repo **Settings → Pages**
5. Enable GitHub Pages from main branch
6. Add custom domain: `studio.evergreenmediadesign.com`
7. GitHub will auto-detect CNAME and provision SSL

### DNS Configuration

Add this CNAME record in Squarespace Domains:

| Host | Type | Value | TTL |
|------|------|-------|-----|
| `studio` | CNAME | `generalmillz.github.io` | Auto |

### Status

- ✅ Subdomain configured
- ✅ CNAME file ready
- ✅ Index.html placeholder
- ⏳ GitHub repo creation (manual step)
- ⏳ DNS propagation

### Support

For issues, contact Evergreen Media Design or GitHub Pages support.
