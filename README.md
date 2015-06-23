#sitemap xml stylesheet
![sitemap1](https://cloud.githubusercontent.com/assets/5467932/8301468/a8ceb2a6-19c0-11e5-9159-55481ceb143a.png)
![sitemap2](https://cloud.githubusercontent.com/assets/5467932/8301470/abe6369e-19c0-11e5-800b-4acc29938726.png)

###Step 1
Upload sitemap.xsl style file to the web root directory

###Step 2
sitemap.xml add style code
```xml
<?xml-stylesheet type="text/xsl" href="http://www.yourdomain.com/sitemap.xsl"?>
```
###demo
```xml
<?xml version="1.0" encoding="UTF-8"?>
<?xml-stylesheet type="text/xsl" href="http://www.yourdomain.com/sitemap.xsl"?>
<sitemapindex xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:image="http://www.google.com/schemas/sitemap-image/1.1">
<sitemap>
<loc>http://www.yourdomain.com/foo1.xml</loc>
<lastmod>2015-06-22</lastmod>
</sitemap>
<sitemap>
<loc>http://www.yourdomain.com/foo2.xml</loc>
<lastmod>2015-06-22</lastmod>
</sitemap>
<sitemap>
<loc>http://www.yourdomain.com/foo3.xml</loc>
<lastmod>2015-06-22</lastmod>
</sitemap>
<sitemap>
<loc>http://www.yourdomain.com/foo4.xml</loc>
<lastmod>2015-06-22</lastmod>
</sitemap>
<sitemap>
<loc>http://www.yourdomain.com/foo5.xml</loc>
<lastmod>2015-06-22</lastmod>
</sitemap>
</sitemapindex>
```
```xml
<?xml version="1.0" encoding="UTF-8"?>
<?xml-stylesheet type="text/xsl" href="http://www.yourdomain.com/sitemap.xsl"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9" xmlns:image="http://www.google.com/schemas/sitemap-image/1.1" xmlns:mobile="http://www.google.com/schemas/sitemap-mobile/1.0" xmlns:xhtml="http://www.w3.org/1999/xhtml">
<url>
<loc>http://www.yourdomain.com/</loc>
<lastmod>2015-06-22</lastmod>
<changefreq>daily</changefreq>
<priority>1</priority>
</url>
<url>
<loc>http://www.yourdomain.com/foo1.htm</loc>
<lastmod>2015-06-22</lastmod>
<changefreq>daily</changefreq>
<priority>0.8</priority>
</url>
<url>
<loc>http://www.yourdomain.com/foo2.htm</loc>
<lastmod>2015-06-22</lastmod>
<changefreq>daily</changefreq>
<priority>0.4</priority>
</url>
</urlset>
```