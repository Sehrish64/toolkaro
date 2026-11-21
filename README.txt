ToolKaro – Website package
==========================
Ready website (sirf HTML, server/database ki zaroorat nahi).

1) DOMAIN BADLO
   Sab files mein "toolkaro.sehrishcreatespk.com" ko apne asli domain se badlo (Find & Replace,
   jaise VS Code mein Ctrl+Shift+H). Ye canonical links, sitemap.xml, robots.txt
   aur contact.html mein hai. "https://" wala hissa rehne do.

2) UPLOAD KARO (free options)
   - Cloudflare Pages ya Netlify: poora folder drag & drop karo.
   - GitHub Pages: files repo mein daalo aur Pages on karo.
   - Ya apni hosting ke public_html mein upload karo. index.html home page hai.

3) ADSENSE
   - Pehle site live karo, phir Google AdSense par apply karo.
   - Approval ke baad AdSense ka script saari .html files mein
     "Google AdSense: apna script yahan paste karo" wale comment ki jagah paste karo.
   - Ad ki jagah: har page par id="ad-top" aur id="ad-bottom" wale div hain.
   - ads.txt mein Google ki di hui line paste karo.
   - About aur Contact mein apni asli details daalo. Thoda traffic aana bhi zaroori hai.

4) GOOGLE SEARCH
   Google Search Console mein site add karo aur sitemap.xml submit karo.

Dhyan rakhne wali baatein
- Tools browser mein chalte hain, bas internet chahiye (libraries cdnjs.cloudflare.com se load hoti hain).
- Image to Text (OCR) aur scanned PDF se text nikalna is package mein shamil nahi hai (AI API maangta hai).
- Video Trimmer/Compressor real-time record karte hain aur WebM file banate hain; iPhone Safari par ye shayad na chalein, Chrome use karo.
- Maine ye tools browser mein khud chala kar test nahi kiye, live karne se pehle har tool ek baar try kar lena.
