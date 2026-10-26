# Connecting the business domain

Production hosting: https://adshnii.github.io/Luxury-Handyman-Hosting/
Intended business domain, already owned: luxuryhandymansolvix.com.

The domain has not been connected by this website task. DNS account access is required for that step. No changes were made to the older WEB site or its custom domain.

1. In the GitHub account’s Pages settings, verify ownership of the domain using the exact TXT record GitHub provides.
2. Follow the current GitHub Pages custom-domain documentation to configure the apex domain and, if desired, www. Use the current GitHub-specified DNS targets, not copied historical values.
3. Preserve existing MX, SPF, DKIM and DMARC records used by business email.
4. Set the custom domain in the Luxury-Handyman-Hosting repository’s Settings → Pages, wait for DNS and certificate checks to pass, and enable Enforce HTTPS.
5. Update canonical URL, Open Graph URL/image URL and JSON-LD URL in index.html; update sitemap.xml and robots.txt. Confirm both the apex and www behavior.
6. Verify the website, business email delivery and links after the change.

Official guide: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
