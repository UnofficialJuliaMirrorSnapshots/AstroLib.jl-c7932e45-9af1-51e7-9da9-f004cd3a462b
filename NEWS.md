History of AstroLib.jl
======================

v0.4.0 (2018-08-17)
-------------------

### Breaking Changes

* Now `AstroLib.jl` requires Julia 0.7.  Support for previous versions has been
  dropped.

v0.3.0 (2017-11-11)
-------------------

### Breaking Changes

* `eq2hor` and `hor2eq` now take as mandatory arguments either the name of an
  observatory in `AstroLib.observatories` or the coordinates (latitude,
  longitude and, optionally, altitude) of the observing site.  Keywords `lat`,
  `lon`, `altitude` and `obsname` are no longer accepted.  There is no more a
  default observing site, you always have to provide it.
