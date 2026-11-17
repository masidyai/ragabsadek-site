RAGAB SADEK - WEBSITE (upload this whole folder to the ROOT of your site)

1. Upload everything, keeping the folders (assets, cv, it, de, ru, ar) and the hidden file .htaccess.
2. Add your domain ragabsadek.com in your host's dashboard and point DNS to it.
3. Turn on HTTPS / "Force HTTPS" in the host's dashboard.
4. Make ragabsadek.com (without www) the main domain; www should redirect to it.
5. In Google Search Console, submit https://ragabsadek.com/sitemap.xml

Host notes
- Apache / cPanel / shared hosting: .htaccess already handles the www redirect and caching.
- Netlify: _redirects handles www. Drag the folder into Netlify Drop.
- Vercel: vercel.json handles www.
- Cloudflare Pages / GitHub Pages: upload as is; set the www -> non-www redirect in their domain settings.
The site must live at the root of the domain (not in a sub-folder).
