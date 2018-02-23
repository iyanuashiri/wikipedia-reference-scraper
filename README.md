# wikipedia-reference-scraper
Wikipedia API wrapper for references

# Motivation

I just graduated from Physiology department, Universty of Ibadan. I started typing my final year project some days before submission
deadline. I made use of Wikipedia for my literature review because each page is supported with enough references. The next task was 
to copy and paste the references. This was a lot of work considering the fact that some pages has over 200 references and I wasn't 
working with just one page. I decided to make use of Wikipedia API wrappers but all the ones I checked didn't do what I needed. So
I decided to write a simple script that scraped Wikipedia page

# Usage

```
>>> from wikipedia_reference_scraper import get_references

>>> get_references('https://en.wikipedia.org/wiki/Blood_pressure#References', 'filename.docx')
``` 
It pulls the references from a Wikipedia page and saves the references in a file

# Tools I Used

Requests

BeautifulSoup

