# Robots.txt of top 1 million websites

These are the /robots.txt files of the top 1 million websites worldwide. This is based on [Ahrefs Rank](https://ahrefs.com/ahrefs-top). The files are in the format `$rank-#siteurl.txt`.

This data was collected in augustus-september 2017 for an unused project / analysis. The complete list of 1M URLs were queried with a timeout of 7 seconds and following redirects. If the site returned a HTTP 200 the file was stored. If you want to learn more about the protocol and how its used you can [read my extensive guide](https://martijnoud.com/robots-txt/).

If you are looking for some fun things to do with this data:

* Most common User-Agent and most blocked
* See what percentage use the default Yoast SEO /robots.txt file
* See how many sites Disallow the root
* How many include a Sitemap (and how many)

Note: Some sites include malicious code in their /robots.txt files. Don't host these files unless you are sure they are served as plain text.