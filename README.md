# Walrus
Write Ahead Log, Transaction Log &amp; Commit Log


## Important terms

* Record - the data stored in the log
* Store - the file we store record in
* Index - the file we store the index entries in
* Segment - the abstraction that ties a store and an index together
* Log - the abstraction that ties all the segments together
