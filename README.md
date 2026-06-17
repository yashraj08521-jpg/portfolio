# Yash Raj — Portfolio

## 🚀 Deploy in 10 minutes

### Step 1 — Formspree (Contact Form)
1. Go to https://formspree.io → Sign up free
2. Create New Form → enter your email
3. Copy your form ID (looks like `xyzabcde`)
4. Open `index.html` → find this line:
   ```
   action="https://formspree.io/f/xyzabcde"
   ```
   Replace `xyzabcde` with your actual ID

### Step 2 — GitHub
1. Go to https://github.com → New repository → name it `portfolio`
2. Upload all files (index.html, vercel.json, README.md)
   OR use terminal:
   ```bash
   git init
   git add .
   git commit -m "launch"
   git branch -M main
   git remote add origin https://github.com/YOURUSERNAME/portfolio.git
   git push -u origin main
   ```

### Step 3 — Vercel
1. Go to https://vercel.com → Sign up with GitHub
2. Click "Add New Project" → import your `portfolio` repo
3. Click Deploy — done!

Your site will be live at: `your-portfolio.vercel.app`

### Step 4 — Custom Domain (optional)
1. Buy domain at namecheap.com (~₹800/year)
2. Vercel dashboard → your project → Settings → Domains
3. Add your domain → follow DNS instructions

## ✏️ How to update content
Just edit `index.html` directly and push to GitHub.
Vercel auto-deploys on every push.
