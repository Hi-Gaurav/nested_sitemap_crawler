# nested_sitemap_crawler

This Python code is designed to extract URLs from nested sitemaps of a website. The script takes a sitemap as an argument and uses regular expressions to extract URLs from the sitemap file. The URLs are then used to access sub-sitemaps and extract URLs from them. The extracted URLs are stored in a CSV file called 'sitemap_extract.csv' with a single column header named 'SitemapURLs'.

# Prerequisites
This script requires the following Python modules:

urllib.request for making HTTP requests
re for regular expression matching
sys for command-line arguments
pandas for creating and manipulating data frames

# Usage
To use the script, run it from the command line with a sitemap URL as an argument. For example:

bash
Copy code
python sitemap_extractor.py https://example.com/sitemap.xml

The script will extract all URLs from the nested sitemaps and store them in a CSV file named 'sitemap_extract.csv' in the same directory as the script.

Note that the script assumes that the sitemap uses the XML format and that URLs are enclosed in <loc> tags.

# Written By Gaurav Tanwar
