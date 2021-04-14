opensearch-extensions
==========================

**AddSearchProvider [got deprecated a long time ago](https://github.com/whatwg/html/issues/713) (showing how often I've updated these). I'll leave this page as is until I figure out what to do (which may be an equally long time).**


Some (well, _five_ right now) search extensions made for OpenSearch (Fx/IE/Cr)

These were done with only moderate experience using OpenSearch, so there may be glaring inefficiencies or inelegancies about them. Please help improve them.


Add to Chrome
-------------

1. Paste the appropriate line below in your address bar, then type `javascript:` in front of it (Chrome may strip out that part when you paste), then press enter.
1. In the popup, it's recommended to set a keyword


Add to Firefox
--------------

1. Open the Web Console (Tools => Web Developer => Web Console)
1. Paste the line in, press enter


Extension Installation Lines
-------

JSTOR
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/opensearch-extensions/master/jstor.xml');`

Gallica (Bibliothèque National de France digitized content)
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/opensearch-extensions/master/gallica.xml');`

HathiTrust
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/opensearch-extensions/master/hathitrust.xml');`

Flickr CreativeCommons
`javascript:window.external.AddSearchProvider('https://raw.githubusercontent.com/triplingual/opensearch-extensions/master/flickr-cc.xml');`

Twitter Latest
`javascript:window.external.AddSearchProvider('https://raw.githubusercontent.com/triplingual/opensearch-extensions/master/twitter.xml');`

TODO
-------

[Epicurious](https://epicurious.com)

[AllMusic](https://allmusic.com)

[Google Scholar](https://scholar.google.com)

[Worldcat](https://worldcat.org) (remembering that this search didn't do well with accented Latin)

Fix to Gallica, which extension is not loading
