# 🌿 GreenHouse Pro - Privacy Policy Setup Guide

## 📋 Overview
This guide will help you set up GitHub Pages to host the Privacy Policy for GreenHouse Pro Android app. Google Play Store **requires** a publicly accessible Privacy Policy URL before you can submit your app.

## 🎯 What You'll Get
- **Privacy Policy URL**: `https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/`
- Professional, responsive design
- Bilingual support (Thai & English)
- Google Play Store compliant

## 📁 Files Included
```
greenhouse-privacy-policy/
├── index.html          # Privacy Policy page (Thai + English)
└── README.md          # This file
```

---

## 🚀 Step-by-Step Setup Instructions

### **Step 1: Create New GitHub Repository**

1. Go to [GitHub](https://github.com) and sign in with your account: **anusitsrb-glitch**

2. Click the **"+"** icon in the top right → **"New repository"**

3. Fill in repository details:
   ```
   Repository name: greenhouse-privacy-policy
   Description: Privacy Policy for GreenHouse Pro Android App
   Public: ✓ (Must be public for GitHub Pages)
   Initialize with README: ✗ (We'll add our own)
   ```

4. Click **"Create repository"**

---

### **Step 2: Upload Files to Repository**

**Option A: Using GitHub Web Interface (Easiest)**

1. In your new repository, click **"uploading an existing file"**

2. Drag and drop both files:
   - `index.html`
   - `README.md`

3. Scroll down, add commit message:
   ```
   feat: add privacy policy page for GreenHouse Pro v1.0.1
   ```

4. Click **"Commit changes"**

**Option B: Using Git Command Line**

```powershell
# Navigate to where you want to clone
cd D:\SmartWebApp

# Clone the repository
git clone https://github.com/anusitsrb-glitch/greenhouse-privacy-policy.git

# Enter directory
cd greenhouse-privacy-policy

# Copy the files you created
# (Copy index.html and README.md into this folder)

# Add files
git add .

# Commit
git commit -m "feat: add privacy policy page for GreenHouse Pro v1.0.1"

# Push to GitHub
git push origin main
```

---

### **Step 3: Enable GitHub Pages**

1. In your repository, click **"Settings"** (top menu)

2. Scroll down to **"Pages"** (left sidebar under "Code and automation")

3. Under **"Build and deployment"**:
   ```
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   ```

4. Click **"Save"**

5. Wait 1-2 minutes for deployment

6. Refresh the page - you should see:
   ```
   ✓ Your site is live at https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/
   ```

---

### **Step 4: Verify Privacy Policy**

1. Visit: `https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/`

2. **Test Checklist**:
   - ✓ Page loads correctly
   - ✓ Both Thai and English versions work
   - ✓ Language switcher works (click buttons)
   - ✓ All sections are readable
   - ✓ Links work (email, website, GitHub)
   - ✓ Mobile responsive (test on phone)

3. If everything looks good → **SUCCESS!** ✅

---

## 📝 Use This URL in Google Play Console

When you submit your app to Google Play Store (Step 10), use this Privacy Policy URL:

```
https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/
```

### **Where to Add in Play Console**:

1. **App Content** → **Privacy Policy**
2. Paste URL: `https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/`
3. Save

---

## 🔧 Customization (Optional)

### **Update Contact Information**

If you need to change contact details, edit `index.html`:

```html
<!-- Find these sections (appears twice - Thai and English) -->
<div class="info-item">
    <strong>📧 Email</strong>
    <p><a href="mailto:support@greenhousepro.com">support@greenhousepro.com</a></p>
</div>
```

Change:
- Email: `support@greenhousepro.com` → Your email
- Website: `https://greenhouse-pro-server-production.up.railway.app` → Your URL

Then commit and push changes:
```powershell
git add index.html
git commit -m "chore: update contact information"
git push origin main
```

Changes will appear on GitHub Pages in 1-2 minutes.

---

## 📱 Privacy Policy Content Overview

The policy covers all Google Play Store requirements:

### ✅ **What's Included**:

**1. Information Collection**
- User account data
- Sensor data (temperature, humidity, etc.)
- Device information
- Usage analytics

**2. How Data is Used**
- Service delivery
- Account management
- Notifications
- Analytics
- Security
- Support

**3. Data Sharing**
- Service providers (Firebase, Railway)
- Legal requirements
- Business transfers
- With user consent

**4. Data Security**
- SSL/TLS encryption
- Password encryption (bcrypt)
- Access control
- Regular backups

**5. Data Retention**
- Active accounts: Retained
- Sensor data: 1 year
- Deleted accounts: 30 days

**6. User Rights (PDPA Compliant)**
- Right to access
- Right to rectification
- Right to erasure
- Right to restrict
- Right to object
- Right to data portability

**7. Children's Privacy**
- Not directed to users under 13
- No knowingly collection from children

**8. Cookies & Tracking**
- Session tokens
- Local storage
- Analytics (no cross-app tracking)

**9. Policy Changes**
- Notification of updates

**10. Contact Information**
- Email, website, organization details

---

## 🎨 Features

### **Professional Design**
- Modern, clean interface
- Emerald green color scheme (matching app branding)
- Logo integration (PremiumLeafLogo from app)
- Responsive design (mobile, tablet, desktop)

### **Bilingual Support**
- Thai (default)
- English
- Easy language switching
- Smooth transitions

### **User-Friendly**
- Clear sections with icons
- Highlight boxes for important info
- Grid layout for contact details
- Scroll-to-top on language switch
- Print-friendly styles

---

## 🔒 Security & Compliance

### **Google Play Store Requirements**: ✅
- [x] Publicly accessible URL
- [x] HTTPS enabled (GitHub Pages)
- [x] Clear privacy disclosures
- [x] Contact information
- [x] Data collection details
- [x] Data usage explanation
- [x] User rights information

### **PDPA Compliance** (Thailand): ✅
- [x] Data subject rights
- [x] Consent mechanisms
- [x] Data retention policies
- [x] Security measures
- [x] Contact for data requests

---

## 📞 Support

If you encounter any issues:

1. **GitHub Pages not deploying?**
   - Wait 2-3 minutes and refresh
   - Check Settings → Pages for error messages
   - Ensure repository is Public

2. **404 Error?**
   - Verify file is named exactly `index.html`
   - Check branch is set to `main` in Pages settings
   - Clear browser cache

3. **Need to update policy?**
   - Edit `index.html`
   - Commit and push changes
   - Wait 1-2 minutes for update

---

## ✅ Next Steps

After setting up Privacy Policy:

### **Step 7**: Prepare Play Console Data
- ✅ Privacy Policy URL: `https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/`
- ✅ Contact Email: `support@greenhousepro.com`
- ✅ App Category: Productivity
- ⏳ Content Rating (questionnaire)
- ⏳ Target Countries: Thailand, etc.

### **Step 8**: Commit & Push Play Store Assets
```powershell
cd D:\SmartWebApp\greenhouse-pro
git add play-store-assets/
git commit -m "feat: add Play Store assets (screenshots, graphics) for v1.0.1 release"
git push origin feat/capacitor-preparation
```

### **Step 9**: Sign up for Google Play Console
- Cost: $25 USD (one-time, lifetime)
- URL: https://play.google.com/console
- Need: Google Account + Credit/Debit Card

### **Step 10**: Upload & Submit to Play Store
- Create new app
- Upload AAB file
- Add screenshots & graphics
- Fill in descriptions
- Add Privacy Policy URL ← **This URL!**
- Complete Content Rating
- Submit for review

---

## 📊 Project Status

**Current**: Step 6/10 Complete ✅

```
Week 5 Progress: 70% Complete
├── ✅ Step 1: Release Keystore
├── ✅ Step 2: key.properties
├── ✅ Step 3: build.gradle
├── ✅ Step 4: Release APK + AAB
├── ✅ Step 5: Play Store Assets
├── ✅ Step 6: Privacy Policy ← YOU ARE HERE
├── ⏳ Step 7: Prepare Play Console Data
├── ⏳ Step 8: Commit & Push
├── ⏳ Step 9: Google Play Console Signup
└── ⏳ Step 10: Upload & Submit
```

---

## 🎉 Congratulations!

You've successfully created and hosted your Privacy Policy! This is a **mandatory requirement** for Google Play Store submission.

**Privacy Policy URL**:
```
https://anusitsrb-glitch.github.io/greenhouse-privacy-policy/
```

**Save this URL** - you'll need it when submitting to Google Play Store!

---

## 📚 Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Google Play Store Privacy Policy Requirements](https://support.google.com/googleplay/android-developer/answer/9859455)
- [Thailand PDPA Overview](https://www.pdpc.gov.sg/overview-of-pdpa/the-legislation/personal-data-protection-act)

---

**Document Created**: February 16, 2026  
**Version**: 1.0.0  
**App Version**: GreenHouse Pro v1.0.1  
**Package**: com.greenhouse.pro

---

© 2026 GreenHouse Pro Development Team  
Bangkok, Thailand
