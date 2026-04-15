# AGENTS

This repository is part of the Goldstonian Concordance Bible scripture data layer.

## Agent Rules

1. Use `data/books.json` for book-level definitions.
2. Use `data/book-index.json` for canonical ordering.
3. Use `data/scripture.ndjson` for verse-level records.
4. Validate structured records against `schemas/scripture.schema.json`.
5. Preserve canonical naming consistency with the wider GCB ecosystem.

## Recommended Tasks

- scripture retrieval
- verse lookup
- chapter assembly
- canonical sequence resolution
- thematic tagging
- knowledge graph ingestion