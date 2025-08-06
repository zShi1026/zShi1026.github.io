# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based academic portfolio website for Zhilin Shi, a Geography M.S. student at Texas A&M University. The site uses the Minimal Mistakes theme hosted on GitHub Pages and showcases research, teaching, and professional information.

## Development Commands

### Local Development
```bash
bundle exec jekyll serve
```
Start local development server (usually runs on http://localhost:4000)

### Build Site
```bash
bundle install
bundle exec jekyll build
```
Install dependencies and build the site for production

### Update Dependencies
```bash
bundle update
```
Update Ruby gems to latest compatible versions

## Site Architecture

### Content Structure
- **Pages** (`_pages/`): Main site pages (research.md, cv.md, teaching.md, etc.)
- **Research Projects** (`_research/`): Individual research project pages using Jekyll collections
- **Posts** (`_posts/`): Blog posts (currently minimal usage)
- **Data** (`_data/navigation.yml`): Site navigation configuration
- **Assets** (`assets/`): Images, PDFs, CSS, and other static files

### Key Configuration
- **_config.yml**: Main Jekyll configuration using Minimal Mistakes remote theme
- **Gemfile**: Ruby dependencies for GitHub Pages deployment
- **index.html**: Homepage with custom splash layout and card-based design

### Theme and Styling
- Uses `mmistakes/minimal-mistakes` remote theme
- Custom skin: "dirt" theme variant
- Custom CSS in `assets/css/custom.css` for additional styling
- Responsive card-based layout on homepage

### Collections
- `research` collection configured in _config.yml with permalink structure `/projects/:name/`
- Research projects are individual markdown files in `_research/` directory

### Navigation
Configured in `_data/navigation.yml` with main menu items:
- Research Interests
- Research  
- Teaching
- CV

## Content Management

### Adding Research Projects
1. Create new markdown file in `_research/` directory
2. Use proper YAML front matter with title, permalink, layout settings
3. Link from main research page (`_pages/research.md`)

### Asset Organization
- Research images: `assets/research_images/`
- CV and documents: `assets/cv/` and `assets/misc/`
- Profile images: `assets/images/`
- Teaching photos: `assets/teaching_photos/`

### Author Profile
Configured in `_config.yml` under `author:` section with bio, avatar, and social links.

## Deployment

Site deploys automatically to GitHub Pages when changes are pushed to the main branch. Uses GitHub Pages' built-in Jekyll processing with the `github-pages` gem.