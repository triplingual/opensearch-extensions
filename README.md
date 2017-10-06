opensearch-extensions
==========================

Some (well, _two_ right now) search extensions made for OpenSearch (Fx/IE/Cr)

These were done with only moderate experience using OpenSearch, so there may be glaring inefficiencies or inelegancies about them. Please help improve them.


Add to Chrome
-------------

1. Paste the appropriate line below in your address bar, then type `javascript:` in front of it (Chrome strips out that part when you paste), then press enter.
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
`javascript:window.external.AddSearchProvider('https://raw.github.com/triplingual/opensearch-extensions/master/gallica-tout.xml');`