Scholar
=======

Update to Christian Kreibich's python parser for Google Scholar - http://www.icir.org/christian/scholar.html

-updated to work with current google scholar urls, python 3.3 and BeautifulSoup4

Use:
python scholar.py "query"

 Options: --count "number to get"     // number to get (currently max of 20 results) - algorithm not recursive
          --author "author name"      // search by author name
          --txt                       // returns results as plain text
          --csv                       // returns results as csv deliminated file
          --csv-header                // returns results as csv deliminated file with header line on top
