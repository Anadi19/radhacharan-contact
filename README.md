# Radhacharan Shakya — digital contact card

This is a static contact-card site for GitHub Pages. No fees, analytics, or external services are required.

## Publish
1. Create a **public** GitHub repository such as `radhacharan-contact`.
2. Upload **all files in this folder** to the root of that repository.
3. In **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/(root)**; save.
4. Your page should appear at `https://YOUR_USERNAME.github.io/radhacharan-contact/` (the exact URL is shown in GitHub Pages settings).

### What the QR does
The supplied `scan-to-save.png` contains a **standard vCard** with the name, phone, email, organization and job-history notes. It works offline and does not depend on the hosted website. It intentionally omits the photo to keep scanning practical.

The **Save contact with photo** button downloads `Radhacharan_Shakya.vcf`, which embeds the supplied photo. Depending on the phone, the user may need to open the downloaded VCF and confirm Add/Create Contact.

If you want the QR to open the webpage instead of importing contact details, generate a *new QR* after publishing using the final Pages URL.
