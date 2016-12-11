# sensorcodecache
This is code pulled out of isetbio when we removed support for the sensor structure. We will want to fix some of this up and push it back in, but perhaps not all.

These routines were removed because they rely on some combination of sensorCreate, sensorGet, sensorSet, pixelSet, lensSet, etc.  That is, they make calls to routines that do not exist in isetbio anymore and thus need to be updated in some way.

The directory hierarchy is set up to mirror isetbio, so it is easy to tell where routine came from.
