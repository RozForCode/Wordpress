<p align="center">Part 1 - More about security</p>

- We need to protect our site from CSRF, DoS, sql injection and other types of attacks
- Some extra security plugins - WP FA2 - login, limit login, admin login url change, inactive logout plugin, wordfence(malware scanning), backup plugins
- Sever-side projection
- Disable PHP Error Reporting - Add a code snippet in the wp-config.php file to hide PHP errors that might expose vulnerabilities.
- Turn Off File Editing in Dashboard - Add another snippet to wp-config.php to disable the built-in code editor
- Protect the wp-config.php File via .htaccess - Add rules to .htaccess to block access to wp-config.php
