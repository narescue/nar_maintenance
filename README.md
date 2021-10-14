# nar_maintenance
Maintenance page for the NAR, and ACS, websites - hosted on github.com via GitHub Pages.

# Fastly
to use this maintenance page, add the contents of index.html to the service defined in Fastly.com. Image, font, and CSS file references in the HTML will point to the files hosted on GitHub Pages in this repo. The URL for this repo's GitHub Pages, is https://narescue.github.io/nar_maintenance/; files must be referenced directly. The index.html file on GitHub Pages will never be referenced, it is here for version control only. Only the supporting files will be referenced the HTML code being copied from index.html into the fastly.com service configuration. 
