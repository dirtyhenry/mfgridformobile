# Introduction #

Before you start customizing the squelette, please be sure you meet all this requirements :
  * A section of your site must be dedicated to a blog, its ID will be refered here as BLOG\_SECTION\_ID
  * A section of your site must be dedicated to a unique contact article, its ID will be refered here as CONTACT\_SECTION\_ID
  * You should have a Feed Burner account
  * You should have a Google Analytics account
  * You should have a Twitter account


# Details #

Please rename some of the files provided in the squelette with your own configuration :
  * contenu/article-5.html should be renamed contenu/article-BLOG\_SECTION\_ID.html
  * contenu/article-8.html should be renamed contenu/article-CONTACT\_SECTION\_ID.html
  * contenu/rubrique-5.html should be renamed contenu/rubrique-BLOG\_SECTION\_ID.html

Configure the files contained in the mfgridformobile folder :
  * mfgridformobile/feedburner.html and mfgridformobile/feedburnerforheader.html should use a proper FeedBurner URL
  * mfgridformobile/googleanalytics.html should contain the script provided by Google Analytics to measure your traffic
  * mfgridformobile/latesttweets.html should contain your own Twitter ID

Provide a good look'n'feel to your site by changing :
  * the default favicon.png icon to one of your own
  * the default rss.png and twitter.png (numerous websites can provide you those, for instance, check [here](http://www.charfishdesign.com/goodies/19-free-hand-drawn-sketch-icons/) or [here](http://www.webdesignerdepot.com/2009/04/24-free-exclusive-vector-icons-handy/))