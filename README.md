# Personal Website - GitHub Pages

This is a simple static website hosted on GitHub Pages.

## Repository Setup

For GitHub Pages personal website (accessible at `https://yourusername.github.io`):

**IMPORTANT**: The repository must be named exactly `yourusername.github.io` where `yourusername` is your actual GitHub username.

## Files

- `index.html` - Main homepage with modern, responsive design
- `README.md` - This documentation file

## Setup Instructions

1. **Create GitHub Repository**:
   - Go to GitHub and create a new repository
   - Name it exactly `yourusername.github.io` (replace with your actual username)
   - Make it public
   - Don't initialize with README (we already have files)

2. **Initialize Git and Push**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Add simple homepage"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository settings
   - Scroll to "Pages" section
   - Select source: "Deploy from a branch"
   - Select branch: "main"
   - Select folder: "/ (root)"
   - Save

4. **Access Your Site**:
   - Your site will be available at `https://yourusername.github.io`
   - It may take a few minutes to deploy initially

## Customization

Edit `index.html` to customize:
- Change the name and content
- Update the styling
- Add more pages
- Add your own links and information

## Local Testing

To test locally, simply open `index.html` in your web browser. 