# Simple HTML Website for Vercel

This is a simple HTML website setup that can be easily deployed to Vercel.

## 🚀 Quick Start

### Option 1: Replace the Homepage
Simply replace `index.html` with your own HTML file. This will become your homepage when deployed.

### Option 2: Add Multiple Pages
- Keep or replace `index.html` as your homepage
- Add more HTML files in the root directory (e.g., `about.html`, `contact.html`)
- Link to them from your homepage using relative paths

## 📁 Project Structure

```
SimpleHtmlWebsite/
├── index.html          # Your homepage (replace this with your own)
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## 🌐 Deploying to Vercel

### Method 1: Using Vercel CLI (Recommended)

1. Install Vercel CLI globally:
   ```bash
   npm install -g vercel
   ```

2. Navigate to your project directory:
   ```bash
   cd c:\Users\maste\Desktop\StatCalc\SimpleHtmlWebsite
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts:
   - Login to your Vercel account
   - Confirm the project settings
   - Your site will be deployed!

### Method 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign up or log in
3. Click "Add New Project"
4. Import your Git repository (push this folder to GitHub first)
   OR
   Drag and drop this folder directly into Vercel

## 📝 How to Use

1. **Replace the homepage**: 
   - Delete or modify `index.html`
   - Add your own HTML content

2. **Add more pages**:
   - Create new `.html` files in the root directory
   - Link to them: `<a href="about.html">About</a>`

3. **Add CSS/JS**:
   - Create `styles.css` or `script.js` files
   - Reference them in your HTML: `<link rel="stylesheet" href="styles.css">`

4. **Add images**:
   - Create an `images` folder
   - Add your images there
   - Reference them: `<img src="images/photo.jpg">`

## 🔄 Updating Your Site

After making changes:
```bash
vercel --prod
```

This will deploy your changes to production.

## 💡 Tips

- Keep all your HTML files in the root directory for simple routing
- Use relative paths for links and assets
- The `vercel.json` file is already configured - you don't need to modify it
- Vercel automatically serves `index.html` as the homepage

## 🆘 Need Help?

- [Vercel Documentation](https://vercel.com/docs)
- [Vercel CLI Documentation](https://vercel.com/docs/cli)

---

**Ready to deploy?** Just run `vercel` in this directory!
