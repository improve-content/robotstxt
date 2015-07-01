# Robots.txt
PHP crawler for robots.txt that checks for a robots.txt disallow or allow. Also contains a robots.txt generator and some examples.

<b>What is Robots.txt?</b>

Robots.txt is a file on websites that tells automated programs crawling around what files they should and should not access/save. These automated programs ("robots") are often search engines, but not always. Given the open nature of the web, the default is permissive when no robots.txt file exists. That means any robot can crawl any file on your website. Even when a robots.txt is provided, it may not always be honored. This code is focused on providing a PHP foundation for crawlers that honors robots.txt.
