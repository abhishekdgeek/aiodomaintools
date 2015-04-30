# aiodomaintools

----------------------------
| Project  Site Tools |
----------------------------

Description: A website statistics site for Web-masters and Digital marketers.

Competitor Sites: sur.ly, domaintools.com, mxtoolbox.com, builtwith.com
 
1. Stack: LAMP or  LNMP.
2. URLs will be similar to mydomain.com/service/domain.name 
3. The site will fetch the database from Alexa top 1 million sites daily and add/update/remove sites daily accordingly.
The site will also save new sites from the search function of the site i.e. if someone searches for a site not present in the database it will be added and checked regularly.
4. Site will have a mysql database with all the updated info.
5. The site will make and keep a screenshot of the analyzed page. Will use : https://github.com/microweber/screen.
6. Have blacklisted words so that we are ad-sense safe.
7. Fetch domain age + social score calculator.
8. There will be a page with last 10 analyzed websites.
9. Crons: Daily task to analyze sites from the alexa (URL: http://s3.amazonaws.com/alexa-static/top-1m.csv.zip 1 mil Alexa sites) and also re-analyze sites that have statistics older than 60 days.
10. Fetch seo titles and descriptions that will be able to contain the domain info or any statistics from the page (ex: domain name, domain title, domain worth, domain pagerank)

This is just the beginning.