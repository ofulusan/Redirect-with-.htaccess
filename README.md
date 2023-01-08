# Redirect-with-.htaccess

````
```
RewriteEngine on
RewriteCond %{HTTP_HOST} ^blog.ofulu.com [NC]
RewriteRule ^(.*)$ https://ofulu.com/ [L,R=301]
```
````

このコードではblog.ofulu.comにアクセスされたときにhttps://ofulu.comにリダイレクトされます。
