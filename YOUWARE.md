# DEFOQA Website Development Guide

## Project Overview
This is a bilingual (English/Japanese) website for DEFOQA, a soccer ball brand with Australian operations. The brand name derives from Portuguese "Defenda o que acredita" meaning "Take a stand for what you believe in."

## Architecture & Structure

### Multi-language Setup
- **English**: `index.html` (main entry point)
- **Japanese**: `jp.html` (Japanese version)
- Both pages share the same CSS file: `css/styles.css`
- Language switching is implemented in both desktop and mobile views

### Key Sections
1. **Hero Section**: Brand introduction with background image
2. **About Section**: Brand story and philosophy
3. **Products Section**: Currently featuring "DEFOQA Birth" - their debut soccer ball
4. **Brand Ambassador Section**: Features Australian female soccer players
5. **Mission Section**: Company values and mission statement
6. **CTA Section**: Call-to-action for contact
7. **Footer**: Contact information and quick links

### Styling Framework
- Uses custom CSS with CSS variables for consistent theming
- Brand colors: Yellow (#f5c518) and Black (#121212)
- Responsive design with mobile-first approach
- Japanese version includes Noto Sans JP font for proper Japanese typography

### Image Assets
- Logo and brand images: `c4m5of45o3_1.png` (main logo)
- Product images: Various soccer ball photos
- Brand ambassador photos: `j8v99jtykn.jpg`, `8ynuh9c0tu.jpg`, `fzrukyb2i3.jpg`
- Hero background: `gzh51tuq3q_1.png`

### Navigation
- Desktop: Full navigation menu with language switcher
- Mobile: Responsive navigation with dedicated language switch button
- Both versions maintain cross-linking between English and Japanese pages

### Content Strategy
- Professional tone with emphasis on quality and conviction
- Brand philosophy centered around "standing up for what you believe in"
- Focus on supporting players at all levels
- Ambassador section highlights professional female soccer players

### Development Notes
- Single product focus: "DEFOQA Birth" soccer ball
- Mobile navigation specifically designed for language switching
- Consistent messaging across both language versions
- Clean, modern design with emphasis on readability and user experience