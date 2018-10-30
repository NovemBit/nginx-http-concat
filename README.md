nginx-http-concat
=================

Overview
--------

WP.com plugin to perform CSS and Javascript concatenation of individual scripts into a single script.

Installation & Configuration
----------------------------

1. Copy the ‘http-concat’ directory and its contents to your WordPress plugins directory.
2. Add to .htaccess this lines.
`RewriteCond %{REQUEST_URI} ^/your_subdomain/_static/$ 
RewriteRule (.*) /your_subdomain/wp-content/plugins/http-concat/ngx-http-concat.php [L]`
3.Activate 2 plugins Css concat and JS concat
4.In nginx-http-concat.php file change defined subdomain

