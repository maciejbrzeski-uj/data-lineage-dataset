# Data Lineage Dataset

This dataset is published for a publication submitted to the VLDB conference.

The database originates from a public example, Adventure Works, provided by Microsoft. You can find it on GitHub: [Adventure Works](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/adventure-works).

The database was enhanced with procedures to display data lineage. Subsequently, the data was processed to create files containing lineage links.

- **File `columns`**: This file contains all table and column names.
- **File `links`**: This file contains data lineage (true links).

We consider all remaining (source, target) pairs that are not included among the lineage links to be non-data lineage pairs.
