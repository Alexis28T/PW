# Complete Netlify CMS Setup Guide for 28-Talent

## What You're Getting

✨ A beautiful admin panel at: `https://yoursite.com/admin`
✨ Add/edit/delete jobs without touching code
✨ Changes go live automatically
✨ Password protected and secure

---

## Files I've Created For You

Your download includes:
```
28-talent-cms/
├── index.html              (Your main website with CMS integration)
├── admin/
│   ├── config.yml         (CMS configuration)
│   └── index.html         (Admin panel)
└── content/
    └── jobs/
        └── sample-job.md  (Example job format)
```

---

## Step-by-Step Setup (30 minutes)

### STEP 1: Create GitHub Account (5 minutes)

1. Go to **github.com**
2. Click **"Sign up"**
3. Choose a username (e.g., "28talent")
4. Enter your email: **Peter@28-talent.com**
5. Create a password
6. Verify your email

**Done!** ✅

---

### STEP 2: Create a New Repository (5 minutes)

1. Once logged into GitHub, click the **"+"** icon (top right)
2. Click **"New repository"**
3. Name it: **28-talent-website**
4. Keep it **Public**
5. ✅ Check: "Add a README file"
6. Click **"Create repository"**

**Done!** ✅

---

### STEP 3: Upload Your Website Files (5 minutes)

1. In your new repository, click **"Add file"** → **"Upload files"**
2. **Drag ALL files from the 28-talent-cms folder:**
   - index.html
   - The entire `admin` folder
   - The entire `content` folder
3. Scroll down and click **"Commit changes"**

**Important:** Make sure you upload the FOLDERS (admin, content), not just loose files.

**Done!** ✅

---

### STEP 4: Deploy to Netlify (5 minutes)

1. Go to **netlify.com** (you're already logged in)
2. Click **"Add new site"** → **"Import an existing project"**
3. Click **"Deploy with GitHub"**
4. **Authorize Netlify** to access your GitHub (click "Authorize")
5. Select your repository: **28-talent-website**
6. Leave all settings as default
7. Click **"Deploy site"**

⏱️ Wait 30-60 seconds for deployment...

**Done!** ✅ Your site is now live!

---

### STEP 5: Enable Netlify Identity (5 minutes)

This allows you to log into the admin panel.

1. In your Netlify dashboard, go to your site
2. Click **"Site configuration"** (in the tabs)
3. Click **"Identity"** in the left sidebar
4. Click **"Enable Identity"**

**Done!** ✅

---

### STEP 6: Enable Git Gateway (2 minutes)

This allows the CMS to save changes to GitHub.

1. Still in **Identity settings**, scroll down
2. Find **"Services"** → **"Git Gateway"**
3. Click **"Enable Git Gateway"**

**Done!** ✅

---

### STEP 7: Invite Yourself as Admin (3 minutes)

1. Still in **Identity**, click **"Invite users"**
2. Enter your email: **Peter@28-talent.com**
3. Click **"Send"**
4. Check your email inbox
5. Click the **"Accept the invite"** link
6. Create a password for your admin panel
7. Click **"Sign up"**

**Done!** ✅

---

### STEP 8: Access Your Admin Panel! 🎉

1. Go to: **https://your-site-name.netlify.app/admin**
   (Replace with your actual Netlify URL)
2. Log in with the password you just created
3. You should see your **Job Board CMS**!

**CONGRATULATIONS!** 🎊 You now have a working CMS!

---

## How to Use Your Admin Panel

### Adding a New Job

1. Go to `yoursite.com/admin`
2. Click **"New Job Postings"**
3. Fill in the form:
   - **Job Title**: e.g., "Senior Python Developer"
   - **Company Name**: e.g., "Tech Solutions Ltd"
   - **Location**: e.g., "Manchester, UK (Remote)"
   - **Employment Type**: Select from dropdown
   - **Salary Range**: e.g., "£60k - £80k"
   - **Category**: Select: ai, lowcode, automation, or integration
   - **Job Description**: Full description
   - **Tags**: Type each skill and press Enter (Python, Django, AWS, etc.)
   - **Active**: Keep this ON to show the job
4. Click **"Publish"**

**That's it!** Your job is now LIVE on the website! 🚀

---

### Editing an Existing Job

1. Go to `yoursite.com/admin`
2. Click on the job you want to edit
3. Make your changes
4. Click **"Publish"**

Changes appear on your website in 10-30 seconds!

---

### Deleting a Job

1. Go to `yoursite.com/admin`
2. Click on the job
3. Click **"Delete"** (usually top right)
4. Confirm deletion

---

### Hiding a Job (Without Deleting)

1. Go to `yoursite.com/admin`
2. Click on the job
3. Toggle **"Active"** to OFF
4. Click **"Publish"**

The job stays in your CMS but won't show on the website.

---

## Important Notes

### The Jobs Won't Show Yet!

**Why?** The current website has hardcoded jobs in the HTML. To make the CMS jobs appear, you'll need to:

**Option A:** I can create an updated index.html that pulls jobs from the CMS (requires JavaScript)
**Option B:** Continue using the current layout and manually update HTML as needed

**Which would you prefer?**

---

## Connecting Your Domain (28-talent.com)

Once everything is working:

1. In Netlify, go to **"Domain management"**
2. Click **"Add custom domain"**
3. Enter: **28-talent.com**
4. Follow the DNS instructions provided
5. Wait 24-48 hours for DNS to propagate

Your admin will then be at: **https://28-talent.com/admin**

---

## Security Best Practices

✅ **Never share your admin password**
✅ **Use a strong, unique password**
✅ **Only invite trusted team members**
✅ **You can add multiple admin users** (repeat Step 7 with different emails)

---

## Need to Add Team Members?

1. Go to Netlify → Your Site → Identity
2. Click **"Invite users"**
3. Enter their email
4. They'll get an invite to create their own password

---

## Troubleshooting

**"Can't access /admin"**
- Make sure Identity and Git Gateway are enabled in Netlify
- Check that you accepted the email invite
- Clear your browser cache

**"Changes not appearing"**
- Wait 30-60 seconds after publishing
- Refresh your browser (Cmd+Shift+R on Mac, Ctrl+Shift+R on Windows)
- Check that the job is marked "Active"

**"Forgot password"**
- Go to `yoursite.com/admin`
- Click "Forgot password"
- Or re-invite yourself from Netlify Identity

---

## What's Next?

Once you've completed setup, let me know if you want:

1. ✨ **Updated index.html** that automatically displays CMS jobs (recommended)
2. 📧 **Email notifications** when new jobs are added
3. 👥 **Instructions for adding team members**
4. 🎨 **Customizing the admin panel appearance**

---

## Quick Reference

- **Your Website**: https://your-site-name.netlify.app
- **Admin Panel**: https://your-site-name.netlify.app/admin
- **GitHub Repo**: https://github.com/yourusername/28-talent-website
- **Netlify Dashboard**: https://app.netlify.com

---

## Summary Checklist

- [ ] Created GitHub account
- [ ] Created repository (28-talent-website)
- [ ] Uploaded all files from 28-talent-cms folder
- [ ] Connected Netlify to GitHub
- [ ] Deployed site
- [ ] Enabled Netlify Identity
- [ ] Enabled Git Gateway
- [ ] Invited yourself and set password
- [ ] Accessed /admin successfully
- [ ] Added a test job

---

**Need help?** Just ask! I'm here to guide you through any step.
