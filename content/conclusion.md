## Conclusion
{:#conclusion}

Our preliminary results show that our filter-based link pruning approach to LTQP over fragmented RDF documents
can be effective for significantly reducing the number of links to traverse.
This leads to a significantly lower amount of data that needs to be downloaded,
and to an overall lower query execution time.
This work opens the possibility for faster traversal-based query execution over fragmented RDF documents,
provided that the data publisher uses hypermedia descriptions to characterize the fragmentation
in a structured manner.
In future work, we will investigate filter-based link pruning for more expressive filter expressions,
and evaluate the approach more extensively over more diverse datasets and queries, comparing our approach with alternative query interfaces.
