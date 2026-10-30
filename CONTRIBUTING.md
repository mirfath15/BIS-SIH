# Contributing

Thanks for your interest in improving BIS Saarthi!

## Adding a new standard to the knowledge base
1. Open `knowledge_base.py`.
2. Add a new `Chunk(...)` entry to `KNOWLEDGE_BASE` with a unique `chunk_id`
   (e.g. `TOY-009`), the `service`, `standard`, `clause`, `title`, `text`,
   `source` and a list of lowercase `keywords`.
3. Keep `text` faithful to the official standard and cite the clause.
4. Run the app locally and test a few queries that should hit your chunk.

## Workflow
1. Fork the repo and create a branch: `git checkout -b feature/my-change`
2. Commit with clear messages: `git commit -m "Add IS 1234 helmet clause"`
3. Push and open a Pull Request describing what and why.

## Reporting issues
Open a GitHub issue with steps to reproduce, the query you used, and what you expected.
