# CLAUDE.md - AI Assistant Guide

## Repository Overview

This repository (`portafolio-imagenes`) is an image assets repository for a personal portfolio website. It stores logos, photos, and graphics used across the portfolio.

**Owner**: arvelaezf
**Language**: Spanish (asset names and descriptions)
**Purpose**: Centralized storage for portfolio image assets

## Repository Structure

```
portafolio-imagenes/
├── *.png          # PNG image files (logos, photos, graphics)
├── *.svg          # SVG vector graphics
├── *.jpeg         # JPEG image files
├── README.md      # Repository description
└── CLAUDE.md      # This file
```

## Asset Categories

### Company/Organization Logos
- `avon-logo.png` - Avon logo
- `BlakHorse.png` - BlakHorse logo
- `Clickgreen.png` - Clickgreen logo
- `CVOportunidades Logo.jpeg` - CVOportunidades logo
- `Cyrculo.png` - Cyrculo logo
- `farmatodo-blue.svg` - Farmatodo logo (SVG)
- `FRSF.png` - FRSF logo
- `Hispacontact.png` - Hispacontact logo
- `La Salle.png` - La Salle institution logo
- `logo-fundacioin.svg` - Foundation logo (SVG)
- `Santos.png` - Santos logo
- `Scout.png` - Scout logo
- `Topem.png` - Topem logo

### Personal/Team Photos
- `Carla.png` - Team member photo
- `Carolina.png` - Team member photo
- `Dayann.png` - Team member photo
- `Fernando.png` - Team member photo
- `Foto Fer A.png` - Personal photo (high resolution)
- `Foto Fer2.png` - Personal photo

### Other Graphics
- `Oportunidades y felicidad organizacional.png` - Organizational graphic
- `ChatGPT Image 29 jul 2025, 01_02_12 p.m..png` - AI-generated image

## Technical Specifications

### Supported Formats
| Format | Use Case | Transparency |
|--------|----------|--------------|
| PNG    | Logos, photos with transparency | Yes (RGBA) |
| SVG    | Scalable vector logos | Yes |
| JPEG   | Photos without transparency | No |

### Image Characteristics
- Most images use 8-bit/color RGBA (PNG with transparency)
- Dimensions vary by purpose:
  - Logos: Typically 500-800px width
  - Photos: 500-600px for portraits
  - High-res assets: Up to 1864x1776px

## Conventions for AI Assistants

### File Naming
- Use descriptive names in Spanish or English
- PascalCase preferred for multi-word names (e.g., `BlakHorse.png`)
- Spaces are allowed but discouraged for web compatibility
- Include purpose/type when helpful (e.g., `farmatodo-blue.svg`)

### When Adding New Images
1. Prefer PNG for logos and images requiring transparency
2. Use SVG for logos when available (better scalability)
3. Use JPEG only for photos without transparency needs
4. Keep file sizes reasonable (optimize before adding)
5. Use descriptive filenames that identify the content

### What NOT to Do
- Do not add code files to this repository
- Do not create subdirectories without explicit request
- Do not modify/edit existing images without permission
- Do not add duplicate images with different names

## Git Workflow

### Commit Messages
- Historical pattern: "Add files via upload"
- Recommended: Be descriptive (e.g., "Add company X logo", "Update team photos")

### Branches
- Main branch contains production assets
- Feature branches: `claude/` prefix for AI-assisted changes

## Integration Notes

This repository is designed to be used as a CDN source for a portfolio website. Images can be referenced via:
- GitHub raw URLs
- GitHub Pages (if enabled)
- Direct repository links

## Quick Reference

| Task | Action |
|------|--------|
| Add new logo | Upload PNG/SVG with descriptive name |
| Add team photo | Upload PNG with person's name |
| Check image info | Use `file <filename>` command |
| List all assets | `ls -la *.png *.svg *.jpeg` |
