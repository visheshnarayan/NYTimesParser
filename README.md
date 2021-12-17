# NYTimesParser

New York Times article parser, uses sitemaps and BS4 to obtain article data.

# Using NYTimesParser

To use this class, create a `NYTimesParser` object

`parser = NYTimesParser()`

To parse articles, use `.parse_articles(start_year, end_year)` method

`df = parser.parse_articles(start_year = 2018, end_year = 2019)`

Method returns `pandas.DataFrame()` object with following atributes:
- date
- headline
- author
- topic
- text
- link
