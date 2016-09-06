# github-search
PHP tool to perform basic search on GitHub.  
Cookie session is mandatory if you don't provide organization name (GitHub requirement).
Note that the search engine is case insensitive.  

```
Usage: php github-search.php [OPTIONS]

Options:
	-c	set cookie session
	-f	looking for file
	-h	print this help
	-o	provide organization name
	-r	maximum number of results, default 50
	-s	search string

Examples:
	php github-search.php -o myorganization -s db_password
	php github-search.php -o myorganization -f wp-config.php -s db_password
	php github-search.php -c "user_session=B0KqycP8LlYORc-s3WFZoH71TG" -f wp-config.php -r 100
```

I don't believe in license.  
You can do want you want with this program.  


![GitHub search example]
(https://raw.githubusercontent.com/gwen001/github-search/master/example.png)