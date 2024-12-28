# Learning Elasticsearch

## Indices, documents, and fields

- The index is a fundamental unit of storage in Elasticsearch - a logical namespace for storing data that share similar characteristics 
- An index is a collectin of documents uniquely identified by a name or an alias

### Documents and fields

- Serializes and stores data in form of JSON documents
- *A document is a set of fields, which are key-value pairs that contain your data*
    - Each has unique ID (can self-create or let Elasicsearch auto-generate)

### Mappings and data types

- Each index has a mapping or schema for how the fields in your documents are indexed
- A `mapping` defines how the data type for each field, how the field should be indexed, and how it should be stored

## Search and analyze data

- Use a combination of API endpoint and a query language to interact with data

### Query Languages

- Query DSL is primary query language for elasticsearch today

#### Query DSL

- JSON-style query language that enables complex searching, filtering, and aggregations
- The `_search` endpoint accepts queries written in Query DSL syntax

##### Search and filter with Query DSL

- Supports wide range of search techniques, some of the main ones are:
- Full-text search
- Keyword search
- Semantic search
- Vector search
- Geospatial search