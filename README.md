# Data Lineage Dataset

This dataset was published in connection with a submission to the AI VLDB Workshop.

The data originates from schema.org. Based on that, we generated sample schemas along with data lineage relationships between them. The generated datasets reflect realistic structure, statistical properties, and common naming conventions used in database schemas.

- **File 'columns'**: Contains all table and column names across the generated schemas.
- **File 'links'**: Contains the true data lineage links (correct mappings) between the schemas.

We assume that all other pairs (source, target) of schema elements not included in the lineage links file are non-data lineage pairs for the respective schema pair.
