# 🚀 Deployment Guide - Juiced Odds

## Quick Deployment to www.juicedodds.com

### Step 1: Connect GitHub to Cloudflare Pages

1. Go to https://dash.cloudflare.com/
2. Sign in to your account
3. Click **"Workers & Pages"** in the left sidebar
4. Click **"Create application"**
5. Click **"Pages"** tab
6. Click **"Connect to Git"**

### Step 2: Select Your Repository

1. Click **"Connect GitHub"**
2. Authorize Cloudflare to access your GitHub
3. Select repository: **juiced-odds**
4. Click **"Begin setup"**

### Step 3: Configure Build Settings

- **Project name:** `juiced-odds`
- **Production branch:** `main`
- **Build command:** (leave empty)
- **Build output directory:** `/`

Click **"Save and Deploy"**

### Step 4: Add Custom Domain

1. In your Cloudflare Pages project, click **"Custom domains"**
2. Click **"Set up a custom domain"**
3. Enter: `www.juicedodds.com`
4. Click **"Continue"**
5. Cloudflare will automatically configure DNS

### Step 5: Configure SSL

1. Go to **"SSL/TLS"** in Cloudflare dashboard
2. Set mode to **"Full"** or **"Full (strict)"**
3. Enable **"Always Use HTTPS"**

### Step 6: Wait for DNS Propagation

DNS changes take 5-30 minutes. Visit:
- https://www.juicedodds.com

---

## 🔄 Making Updates

1. Edit files in your GitHub repository
2. Commit changes
3. Cloudflare automatically redeploys (1-2 minutes)
4. Changes are live!

---

## ✅ Verification Checklist

- [ ] Site loads at www.juicedodds.com
- [ ] All 6 games are accessible
- [ ] Homepage displays correctly
- [ ] Admin panel works
- [ ] SSL certificate is active (https)

---

**You're live! 🎉**
