DUNIYA SOLUTIONS WEBSITE - DEPLOYMENT NOTES

Files
- index.html: homepage
- about.html, services.html, training.html, case-studies.html, contact.html
- privacy-policy.html, terms.html, cookie-notice.html
- 404.html, robots.txt
- assets/site.css, assets/site.js, assets/logo.svg
- favicon.svg: simple blue square with a white D

Deploy the complete folder contents to the root of your Vercel static site. Keep the assets folder in the same location as the HTML files.

Contact details included as supplied:
Email: contact@duniyasolutions.in
Phones: +91 7609 903 328; +91 81178 84450
Office address: CDA Sector-7, F/107, Cuttack, Odisha 753014
Legal identity: INFINITUM DUNIA SOLUTIONS INDIA LLP | LLPIN ACR-6000 (LLPIN taken from the provided website review).

IMPORTANT FORM BEHAVIOUR
Contact forms use a mailto workflow. They open the visitor's configured email application with the entered information. The website does not send the form to a backend or store it. The visitor must review and send the email. To accept enquiries directly on the website, connect a form backend or service and update the privacy notice.

CASE STUDIES
The case-studies page deliberately contains anonymized, illustrative solution patterns and does not claim named client endorsements or quantified results. Replace or expand these only with verified project facts and appropriate client authorization.

LEGAL REVIEW
Privacy, terms, and cookie pages are baseline website notices, not legal advice or a compliance certification. Review them against the actual operating setup and applicable legal requirements before publication.

DOMAIN CONFIGURATION
Preferred production URL: https://www.duniyasolutions.in/
Canonical URLs and sitemap.xml use the www domain. The included vercel.json permanently redirects requests for the apex domain (duniyasolutions.in) to the matching www URL.

Before deploying, add both duniyasolutions.in and www.duniyasolutions.in to the Vercel project under Settings > Domains, and configure the DNS records exactly as Vercel displays. The redirect will only work once both hostnames resolve to this Vercel project.

After deployment, submit https://www.duniyasolutions.in/sitemap.xml in Google Search Console.