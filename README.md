
## 🚀 Quick Start Guide

### Step 1: Test Locally
1. Download all 4 files to a folder
2. Open `admin.html` in your browser to manage content
3. Open `index.html` to view your directory

### Step 2: Use the CMS
1. **Add Creators**: Fill the form in "Add Creator" tab
2. **Manage Content**: Edit/delete in "Manage Creators" tab  
3. **Export Data**: Copy JSON from "Export Data" tab
4. **Update**: Replace `data/creators.json` with new JSON

### Step 3: Deploy to Cloudflare Pages

#### A. Create GitHub Account
1. Go to [github.com](https://github.com) → Sign up
2. Verify your email

#### B. Create Repository
1. Click "+" → "New repository"
2. Name: `apostate-directory`
3. Public repository
4. Click "Create repository"

#### C. Upload Files
1. In your repository, click "Add file" → "Upload files"
2. Drag and drop all 4 files:
   - `index.html`
   - `admin.html` 
   - `data/creators.json`
   - `README.md`
3. Commit message: "Initial setup"
4. Click "Commit changes"

#### D. Connect Cloudflare Pages
1. Go to [dash.cloudflare.com](https://dash.cloudflare.com)
2. "Workers & Pages" → "Create application" → "Pages"
3. "Connect to Git" → Select your repository
4. Click "Begin setup"

#### E. Build Settings
- **Build command:** (leave empty)
- **Build output directory:** (leave empty) 
- **Root directory:** (leave as is)
- Click "Save and Deploy"

#### F. Access Your Site
- Website: `https://your-project.pages.dev`
- CMS: `https://your-project.pages.dev/admin.html`

## 🛠 Daily Management

### Using the CMS:
1. Open `admin.html` (locally or on your live site)
2. Add/edit creators using the form
3. Export JSON data
4. Update `data/creators.json` with new data
5. Push changes to GitHub

### Git Commands (Optional):
```bash
# Clone your repo
git clone https://github.com/yourusername/apostate-directory.git

# Make changes, then:
git add .
git commit -m "Updated creators"
git push
