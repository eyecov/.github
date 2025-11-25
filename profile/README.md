# Covflux

**Covflux is a unified, diff-aware code coverage system designed for codebases in motion.**

It ingests coverage data from multiple sources, stores it in a compact SQLite format, and exposes it to editors, CI pipelines, and AI tools.  
Covflux tracks how coverage shifts as code evolves, making it easier to understand, visualize, and maintain test quality over time.

This organization hosts the Covflux ecosystem:

- **covflux-core** – shared schema, data model, and utilities  
- **covflux-php** – ingestors and tooling for PHP-based projects  
- **covflux-vscode** – VS Code integration for real-time coverage visualization  
- **covflux-mcp** – AI-facing coverage querying and analysis  

The project is in early development, and more components will appear here as the system takes shape.

Stay tuned — coverage is about to get fluent.
