## Different implementations of Debian archive file reader

I was working on a ruby script that requires reading .deb files
and for that reason, I tested and several libarchive implementations.
Those are put down here.

### Fastest

I've found `libarchive-ruby-swig` to be the fastest of all of those 