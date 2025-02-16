# simplekml2 is a python package which enables you to generate KML with as little effort as possible.

> This project is a Fork from [https://github.com/tjlang/simplekml](https://github.com/tjlang/simplekml) but has support for Python 3.8 and superior

At the time of making this package nothing was available (at least I could not find anything) that could create KML files easily. You needed a lot of bloated code to even create a simple point. This is understandable because the KML standard is quite extensive, but what if you just work with the simple elements of KML like Document, Folder, Point, LineString and Polygon? This package supports those elements and everything documented in the KML Reference. With simplekml creating a KML file containing a point as simple as::

    import simplekml
    kml = simplekml.Kml()
    kml.newpoint(name="Kirstenbosch", coords=[(18.432314,-33.988862)])
    kml.save("botanicalgarden.kml")

See the http://simplekml.readthedocs.org for usage and reference.
Visit http://code.google.com/p/simplekml/ for the homepage.
