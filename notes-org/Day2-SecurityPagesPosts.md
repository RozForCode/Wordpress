<p align="center">Part 1 - More about security</p>

- We need to protect our site from CSRF, DoS, sql injection and other types of attacks
- Some extra security plugins - WP FA2 - login, limit login, admin login url change, inactive logout plugin, wordfence(malware scanning), backup plugins
- Sever-side projection
- Disable PHP Error Reporting - Add a code snippet in the wp-config.php file to hide PHP errors that might expose vulnerabilities.
- Turn Off File Editing in Dashboard - Add another snippet to wp-config.php to disable the built-in code editor
- Protect the wp-config.php File via .htaccess - Add rules to .htaccess to block access to wp-config.php

<p align="center">Part 2 - Pages</p>
** Creating a new Page can be done in 3 ways:**

- GUI - pages>all Pages> add new page
- GUI - menu> new > page
- GUI - new page option after publishing a page

** Designing and Customizing a page **

- Wire frame - visual outline of what will be included in the page
- add title, then build page with blocks, play around with block settings and styles
- column block can have blocks nested within

** Managing Pages **

- Pages have multiple options in pages menu, for searching and also have quick edit options.
- Can change url, title, order, status
- For multiple pages at a time, select them and use GUI options ( pretty intuitive)

<p align="center">Part 3 - Posts</p>
Quite similar to pages but used to different purposes

_Difference between pages and posts_

- Pages are static whereas posts are for timely content

- Creation is similar to pages

** Some facts **

- Different themes treat images differently, but there are plugins that can be used to fix this
- To manage use Posts in the left side menu list and rest is similar to pages
- Manage posts based on their meta-data
- Categories - hierarchical, if not assigned to a post, wordpress will automatically assign it non categorized
- Also manage tags similarly
- Categories are broad topic groupings, while tags are specific keywords describing post details.
