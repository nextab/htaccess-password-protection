# htaccess-passwortschutz
## Komplettes Toolkit, um eine Entwicklungsumgebung (oder beliebige Webseite) unter einen Passwortschutz per .htacces zu setzen

1. Upload path.php to your webspace
2. Open yourdomain.com/path.php
3. Copy the server path from the open browser window to .htaccess
4. DELETE path.php from your webspace!!!
5. Upload .htpasswd to the root of your website
6. Download the .htaccess of your website (this is important so your WordPress permalink settings do not get lost; if you are not using WordPress, skip this step).
7. Add the contents of the .htaccess in this repo to your .htaccess (I'd recommend at the very beginning)
8. Paste the server path to .htpasswd in your new .htaccess
9. Upload changed .htaccess

=> To access your protected website, enter the username "test" and the password "t3stpwd".

---
Additional info:
If you prefer to have ONLY wp-login.php under password protection, remove the "#" before the ``<FilesMatch>`` commands in the .htaccess. 
WARNING: DO NOT keep a password protection if users can register on your site and / or they can do stuff that requires AJAX (e.g. **online shops with WooCommerce or most contact form plugins**).

---

If you would like to use different login credentials, use a .htaccess generator, e.g. https://www.web2generators.com/apache-tools/htpasswd-generator
