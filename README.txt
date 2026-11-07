# MF Advertising Services - Official Website Deployment Guide

Yeh website GoDaddy ya kisi bhi web hosting server ke liye ready-to-deploy static website bundle hai.

## Files List
- `index.html`: Website ki main HTML, CSS (Tailwind), aur JavaScript code file.
- `README.txt`: Deployment instructions guide.

## GoDaddy Hosting (cPanel) par Upload karne ka tareeqa:
1. Apne **GoDaddy** account mein login karein.
2. **My Products** > **Web Hosting** > **Manage** (cPanel) par click karein.
3. cPanel dashboard mein **File Manager** open karein.
4. **public_html** folder ke andar jayein.
5. Is ZIP file ko upload karein aur extract karein, ya direct `index.html` file ko `public_html` folder ke andar upload kar dein.
6. Apne domain ko browser mein check karein, website instantly live ho jayegi!

## Free Hosting Alternate (Bina cPanel ke):
Agar aapke paas hosting plan nahi hai:
1. `index.html` ko **Netlify** ya **Vercel** par drag-and-drop karein.
2. Apne GoDaddy domain ke DNS settings mein A Record / CNAME add karein.
