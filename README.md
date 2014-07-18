Gridsquare
==========

This module provides an easy way to convert between the [http://en.wikipedia.org/wiki/Maidenhead_Locator_System](Maidenhead Locator System) (gridsquares) and the [World Geodetic System](http://en.wikipedia.org/wiki/World_Geodetic_System) (WGS-84) coordinate
system.


Usage
-----

The module provides to primary functions for the conversion: `to_latlng` and `to_gridsquare`.

    >>> import gridsquare as gs
    >>>
    >>> coords = gs.to_latlng("CN85jc")
    >>> print coords
    (45.104, -123.208)
    >>> gridsquare = gs.to_gridsquare(coords[0], coords[1])
    >>> print gridsquare
    "CN85jc"


License
-------
See the `LICENSE` file accompanied by the module for more information.


Author
------
Evan Fosmark (K7FOS)

_All pull-requests will be put into consideration._