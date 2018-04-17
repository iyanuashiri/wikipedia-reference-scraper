# wikipedia-reference-scraper
[Wikipedia](https://www.wikipedia.org/) API wrapper for references

# Motivation

I just graduated from Physiology department, [University of Ibadan](https://www.ui.edu.ng/). I started typing my final year project some days before submission
deadline. I made use of Wikipedia for my literature review because each page is supported with enough references. The next task was
to copy and paste the references. This was a lot of work considering the fact that some pages has over 200 references and I wasn't
working with just one page. I decided to make use of Wikipedia API wrappers but all the ones I checked didn't do what I needed. So
I decided to write a simple script that scraped Wikipedia page.

# Usage

## Python Interactive Shell

```
>>> from wikipedia_reference_scraper import WikipediaReferenceScraper as wrs

>>> wrs().write_to_document('https://en.wikipedia.org/wiki/Blood_pressure#References', 'filename.docx')
```

## Through the Command Line (with python-fire)

```
$ python wikipedia_reference_scraper.py write_to_document https://en.wikipedia.org/wiki/Blood_pressure#References filename.docx
```

It pulls the references from a Wikipedia page and saves the references in a file.

# Tools I Used

Requests

BeautifulSoup

python-fire
