##资料

###Paper
1. [VIPS a Vision-based Page Segmentation Algorithm](http://research.microsoft.com/apps/pubs/default.aspx?id=70027)
2. [Web Content Cleaning](http://is.muni.cz/th/139654/fi_m/thesis.pdf)
3. [Boilerplate Detection using Shallow Text Features](http://www.l3s.de/~kohlschuetter/publications/wsdm187-kohlschuetter.pdf)
4. [CoreEx: Content Extraction from Online News Articles](http://ilpubs.stanford.edu:8090/832/1/2008-15.pdf)

###Code
1. [boilerpipe](https://code.google.com/p/boilerpipe/)

        The boilerpipe library provides algorithms to detect and remove the surplus "clutter" (boilerplate, templates) around the main textual content of a web page.

        The library already provides specific strategies for common tasks (for example: news article extraction) and may also be easily extended for individual problem settings.

        Extracting content is very fast (milliseconds), just needs the input document (no global or site-level information required) and is usually quite accurate.

2. [BET](https://github.com/aidanf/BTE)

        BTE is a python module for automated extraction of body text from web pages. By body-text I mean extract the main textual content from the page and throw away all the extra non-important stuff like sidebars, navigation bars, header, footer, etc. It can also be used to generate short teasers/summaries.

        I wrote BTE about 7 years ago and I don't use it or support it anymore. It worked pretty well when I wrote it originally but I'm not sure how well it works on todays web pages, which may have different tag distributions (e.g. less tables, more javascript).

###Blog
1. [The Easy Way to Extract Useful Text from Arbitrary HTML](http://ai-depot.com/articles/the-easy-way-to-extract-useful-text-from-arbitrary-html/)