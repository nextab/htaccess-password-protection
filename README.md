# htaccess-passwortschutz
## Komplettes Toolkit, um eine Entwicklungsumgebung (oder beliebige Webseite) unter einen Passwortschutz per .htacces zu setzen

1. Upload path.php to your webspace
2. Open yourdomain.com/path.php
3. Copy the server path to .htpasswd from the open browser window
4. DELETE path.php from your webspace!
5. Upload .htpasswd to the root of your website
6. Download the .htaccess of your website
7. Add the contents of the .htaccess in this repo to your .htaccess (I'd recommend at the very beginning)
8. Paste the server path to .htpasswd into your new .htaccess
9. Upload changed .htaccess

---
Additional info:
If you prefer to have ONLY wp-login.php under password protection, remove the "#" before the ``<FilesMatch>`` commands in the .htaccess. DO NOT keep a password protection if users can register on your site and they can do stuff that requires AJAX (e.g. online shops with WooCommerce).
