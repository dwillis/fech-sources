# FechSources
Source CSV files for Federal Election Commission electronic filing headers and rows.

This collection of comma-delimited files is meant to be included in [Fech](https://github.com/NYTimes/Fech), a Ruby library for parsing [F.E.C. electronic filings](http://www.fec.gov/finance/disclosure/efile_search.shtml), or in similar libraries. The files contained within are the same files in the `sources` directory in earlier version of Fech itself. They have been moved to a separate repository so that it's not necessary to release a new version of the gem each time the F.E.C. updates its filing formats, and also to eliminate the need for non-Ruby libraries to create and maintain their own collections of CSVs.
