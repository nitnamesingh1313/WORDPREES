Pages
• WP uses the template page.php BUT verify first if a specific template has been created (based on name, then on id)
• If no specific template = page.php is used
• Since slug and ID could have been changed = preferable to use custom pages templates (for a while)
Home page
• The home page = managed in a special way using the template front-page.php • If the template isn't there = WP check swhat page has been set as home page :
  Archive
•
If home page is a page : WordPress uses page.php. If home page is a blog : WordPress uses home.php.
This can be changed in Settings > Reading.
 • 99% of time, archive.php will be used
• A category, a label or a specific author can be targeted using the slug or the ID
Single
• WP uses single.php
• Also possible to use single-post.php
(no points unless, maybe, if custom post types are used)
6:05
Naming Conventions:
Archive : Displays sorted by categories, tags, author, date, etc using archive.php.
Single : Content of a page uses page.php, and content of a post uses single.php.
Blog's main : which is a special archive, uses home.php.
Web site's home page : uses front-page.php.
404 page : uses 404.php.
Search result page : uses search.php.
