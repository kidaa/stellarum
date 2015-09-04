The CATALOGUS STELLARUM is a writing project which I posted on my twitter account [@FSVO](https://twitter.com/FSVO) in 2012: I collected
every star with a proper name (Antares, Betelgeuse etc) from a couple of different sources, and then provided
a strange or amusing precis of each, in alphabetical order.

The code here is an attempt to build an interesting web visualisation of the list.  I pulled the archive of FSVO tweets
from my Pinboard account, and then wrote a script to go through the list of stars and do Wikipedia searches
to get the astronomical coordinates, apparent magnitude and stellar category (colour) for each star.

Then I used the excellent d3 Javascript visualisation toolkit to render the stars in a stylised celestial
sphere.

You can play with it here: [http://stellarum.mikelynch.org/](http://stellarum.mikelynch.org/)
