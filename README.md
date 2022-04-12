# Forest_Classifier

Land use classification is an important task to understand
our changing environment. One approach to this involves the use of data from aerial sensors
that captures different spectral reflectance properties of the ground below. From this data,
the land type can be classified.

The data used with this model includes 27 spectral properties and an overall classification of land type, which can be
one of:

* s: ‘Sugi’ forest;
* h: ‘Hinoki’ forest;
* d: ‘Mixed deciduous’ forest;
* o: ‘Other’ non-forest land.

Using this data two multi-class classifiers classify land type from the
spectral data. These classifiers are be:
1. A K-Nearest Neighbours Classifier;
2. An ensemble of binary classifiers.
