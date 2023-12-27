# AlphaNet Software Website

This is the public website for AlphaNet Software at www.alphanetsoftware.com. The website is hosted using Github Pages.

To edit the website, edit the index.html file and they should be reflected at www.alphanetsoftware.com.

For troubleshooting, check GitHub Pages settings:
- In GitHub, go to settings>pages
- The source should be set to 'main'
- The custom domain should be set to 'www.alphanetsoftware.com'
- Enforce HTTPS should be checked

Also check your domain name provider DNS settings:
- Go to Manage Domain -> Advanced DNS settings
- CNAME record should have host 'www' and value 'alphanetsoftware.github.io and TTL 'automatic'
- There should be four A record entries with Host set to '@' and TTL 'automatic'. Values are
    - Value: 185.199.108.153
    - Value: 185.199.109.153
    - Value: 185.199.110.153
    - Value: 185.199.111.153
