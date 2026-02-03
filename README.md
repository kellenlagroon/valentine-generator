[README.md](https://github.com/user-attachments/files/24998011/README.md)
# Valentine's Day Generator 💝 

A fun, interactive Valentine's Day website where you can create personalized Valentine pages to send to someone special!

## Features

- 🎨 Beautiful gradient design
- 💕 Personalized messages with names
- 🎉 Confetti explosion on "Yes"
- 🖱️ Interactive "No" button that moves away (desktop)
- 📱 Shrinking "No" button on mobile
- 🔗 Shareable custom links

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `valentine-generator`)
5. Make it **Public**
6. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface (Easiest)**

1. On your new repository page, click "uploading an existing file"
2. Drag and drop both files:
   - `generator.html`
   - `valentine.html`
3. Scroll down and click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Navigate to the folder with your files
cd /path/to/your/files

# Initialize git
git init

# Add your files
git add generator.html valentine.html README.md

# Commit your files
git commit -m "Initial commit: Valentine generator"

# Connect to your GitHub repository (replace with your URL)
git remote add origin https://github.com/YOUR-USERNAME/valentine-generator.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (top menu)
3. Scroll down and click "Pages" (left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and "/ (root)"
6. Click "Save"

### Step 4: Access Your Website

After a few minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/valentine-generator/generator.html
```

Replace `YOUR-USERNAME` with your actual GitHub username.

## How to Use

1. Go to your GitHub Pages URL (the generator.html page)
2. Enter your Valentine's name
3. Click "Generate Link"
4. Copy the personalized link
5. Send it to your Valentine!

When they click the link, they'll see a personalized page with their name asking them to be your Valentine! 💕

## File Structure

```
valentine-generator/
├── generator.html    # Main page to create custom links
├── valentine.html    # The Valentine question page
└── README.md        # This file
```

## Customization

Feel free to customize:
- Colors in the CSS (look for gradient and color values)
- The success GIF URL (find a different GIF on Giphy)
- Text messages
- Button styles

## Tips

- Make sure both files are in the same folder/repository
- The generator creates links with `?name=` parameter
- Works on both desktop and mobile devices
- Share directly or via social media!

## License

Free to use for personal purposes. Spread the love! 💝
