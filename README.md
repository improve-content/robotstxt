# Robots.txt
PHP crawler for robots.txt that checks for a robots.txt disallow or allow. Easily call the PHP function with your robot's user-agent and the URL your crawler is planning to visit.

<b>What is Robots.txt?</b>

Robots.txt is a file on websites that tells automated programs crawling around what files they should and should not access/save. These automated programs ("robots") are often search engines, but not always. Given the open nature of the web, the default is permissive when no robots.txt file exists. That means any robot can crawl any file on your website. Even when a robots.txt is provided, it may not always be honored. This code is focused on providing a PHP foundation for crawlers that honors robots.txt.

<b>What Features Does The Robots.txt Project Include?</b>
<ul>
<li>Support for customized user-agent string</li>
<li>Supports robots.txt files that provide rules for multiple user-agents at one time</li>
<li>Returns the host directive</li>
<li>Returns the crawl-delay directive</li>
<li>Returns any declared sitemaps</li>
<li>Ignores comments</li>
<li>Supports specific allow directives that override less specific disallows (based upon length)</li>
