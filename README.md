When building data structures for use with interactive data manipuluation, 
it is often handy to have data structures that can be efficiently indexed
by position (like a vector) as well as readably indexed by name (like a
hash table). The NamedIndex type here maps unique names to integer 
indexes, looking up ByteString indexes in a Dict and passing other
index types through. The NamedVector type implements a simple use case,
with a backing vector of an arbitrary type. 

Written by Tom Short (@tshort) and Harlan Harris (@HarlanH).

See [Pull Request 1190](https://github.com/JuliaLang/julia/pull/1190) for discussion.

See LICENSE.md for the software license.