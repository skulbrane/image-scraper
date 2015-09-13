# image-scraper
Python script to scrap images 

## Developer's guide
```
$ git clone https://github.com/NaveenKarippai/image-scraper
$ cd image-scraper
$ python ImageScraper.py
```

## Information

### ImageDownloader.py
* Read input locations from command-line, stdin, or as a file structured according to one of the following formats:
    * [csv](https://en.wikipedia.org/wiki/Comma-separated_values)
    * [JSON](https://en.wikipedia.org/wiki/JSON)
    * A list of [URL](https://en.wikipedia.org/wiki/Uniform_resource_locator) addresses delimited by a ***single newline***

    *We should make some effort to provide a standard interface for defining and parsing additional formats
    *Do not assume the data file is on the local disk, that permissions are valid, etc...

### ImageScraper.py
* Instantiate class with url of webpage to scrap

### Dependencies
* urllib
* urllib2
* os
* BeautifulSoup
* re

