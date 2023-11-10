Using an .htaccess on the root folder

```
RewriteEngine on
RewriteCond %{REQUEST_URI} !^/index.html$
RewriteRule . / [R=302,L]
```

The condition and rule is that if the request does not match index.html it will redirect whatever to it
