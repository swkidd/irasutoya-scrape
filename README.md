# irasutoya-scrape

#public sites (hosted on S3)  
[random images](https://irasutoya-images.s3.amazonaws.com/index.html)  
[images by grade](https://irasutoya-images.s3.amazonaws.com/joyo.html)  

A simple static site for studying Japanese through irasutoya.com. Images were scraped and data analyzed through Python. Clicking on an image will display its description, and clicking on a Japanese word will display its reading and definition.  

site/joyo.html contains all irasutoya images sorted by which kanji they contain, and the grade of each kanji.  
site/index.html shows a random page of images.  

HTML generated with Jinja. NLP using spacy. Definitions come from [WWWJDIC](http://nihongo.monash.edu/cgi-bin/wwwjdic?1C)  
