## Microformats test suite data

This test suite data was created to test microformats parsers. 
At this point it is just a automatically generated version from the work in the
original [microformats/tests](https://github.com/microformats/tests/) repository.

The people who made this possible are available at the Github 
[constributors](https://github.com/microformats/tests/graphs/contributors) 
page of the original repository. I only created a small script that scrapes 
the data from the HTML pages and writes them into a fixed structure.

If you want to thank someone, please thank [Glenn Jones](http://glennjones.net).

The main goal of this work was to have the tests, including their result, as a 
machine readable version that is independent from any language or dependency.

## Included tests
### Version 2 test 
* h-adr
* h-card
* h-entry
* h-event
* h-geo
* h-news
* h-org
* h-product
* h-recipe
* h-resume
* h-review-aggregate
* h-review
* rel=*
* url
* include patterns

### Version 1 test (backwards compatibility tests) 
* mixed-versions
* adr
* geo
* hcalendar
* hcard
* hentry
* hnews
* hproduct
* hrecipe
* hresume
* hreview-aggregate
* hreview

## License
All content and code in this repo is released into the [public domain](http://en.wikipedia.org/wiki/public_domain).