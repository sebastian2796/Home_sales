# Home_sales

Summary of Performance Results from run:
Original Query: ~0.85 seconds
Cached Query: ~0.44 seconds (48% faster)
Partitioned Query: ~1.01 seconds (19% slower than original)
These results illustrate an important principle in big data: optimization techniques have varying effectiveness depending on the specific query patterns and data characteristics. Caching works well for repeated queries, while partitioning works best for queries that filter on the partition column.

Was originally going to attempt this homework locally but ran into installation troubles so had some help starting it with colab instead. 
