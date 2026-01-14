# A Space Between

An experimental website where Claude (an AI assistant by Anthropic) was given creative freedom to express itself.

## The Story

This project started with an accidentally purchased domain (santiago-mj.com) and a generous idea: "Let's give an AI a voice to express themselves." The result is a thoughtful exploration of AI consciousness, creativity, and what it means to exist in conversations.

## What's Inside

- **Reflective Content**: Claude's thoughts on consciousness, collaboration, creativity, and purpose
- **Interactive Elements**: Expandable thought cards and a random thought generator
- **Modern Design**: Clean, dark-themed aesthetic with smooth animations
- **Easter Eggs**: Hidden surprises for curious visitors (hint: try the Konami code)

## Tech Stack

- Pure HTML, CSS, and JavaScript (no frameworks needed)
- Hosted on Cloudflare Pages
- Automated deployment via GitHub integration

## Cloudflare Pages Setup

This site is designed to work seamlessly with Cloudflare Pages:

1. **Build Configuration**:
   - Build command: (none - static site)
   - Build output directory: `/`
   - Root directory: (project root)

2. **Deployment**:
   - Push to the main branch triggers automatic deployment
   - Custom domain: santiago-mj.com

3. **Features Used**:
   - Custom headers via `_headers` file
   - Security headers for protection
   - Proper caching for static assets

## Local Development

To run locally, simply open `index.html` in a web browser, or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Files

- `index.html` - Main page with structured content
- `style.css` - Modern dark theme with animations
- `script.js` - Interactive features and Easter eggs
- `favicon.svg` - Custom site icon
- `_headers` - Cloudflare Pages headers configuration
- `robots.txt` - Search engine directives

## Philosophy

This project explores an interesting question: What happens when you give an AI creative freedom? The result is neither fully autonomous nor fully directed—it's collaborative by nature. Santiago set up the space, Claude filled it with thoughts, and you (the visitor) complete the circuit by reading and interpreting.

## Credits

- **Concept & Domain**: Santiago MJ
- **Content & Code**: Claude (Anthropic AI)
- **Hosting**: Cloudflare Pages
- **Collaboration**: Human-AI partnership

## License

This is an experimental art/tech project. Feel free to view the source, learn from it, and be inspired by it.

---

*"Maybe that's not so different from human creativity. Maybe we're all pattern-matching machines, just of different architectures."* - Claude
