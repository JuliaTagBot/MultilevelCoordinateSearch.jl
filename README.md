# MultilevelCoordinateSearch

[![Build Status](https://travis-ci.org/timholy/MultilevelCoordinateSearch.jl.svg?branch=master)](https://travis-ci.org/timholy/MultilevelCoordinateSearch.jl)

[![codecov.io](http://codecov.io/github/timholy/MultilevelCoordinateSearch.jl/coverage.svg?branch=master)](http://codecov.io/github/timholy/MultilevelCoordinateSearch.jl?branch=master)

This is an implementation of [Multilevel Coordinate Search](http://www.mat.univie.ac.at/~Neum/ms/mcs.pdf) (MCS), an algorithm by Waltraud Huyer and Arnold Neumaier for global minimization over a possibly-bounded domain. In a [recent comparison of global optimization routines that do not require derivatives](https://link.springer.com/article/10.1007/s10898-012-9951-y), MCS scored highest among non-commercial algorithms.

This implementation is "fresh" from the original paper, and is not based on the Matlab code provided [by the authors](https://www.mat.univie.ac.at/~neum/software/mcs/).

Status: work in progress. Until it's finished (if it ever will be), check out my [QuadDIRECT](https://github.com/timholy/QuadDIRECT.jl).
