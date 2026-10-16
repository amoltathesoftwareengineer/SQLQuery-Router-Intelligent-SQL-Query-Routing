
# SQLQuery-Router

A prototype for classifying SQL statements and routing them to configured database connections.

## Overview

SQLQuery-Router explores how database applications can select an appropriate database connection based on query type and routing rules.

## Planned Features

- Identify common SQL statement types
- Configure read and write routes
- Support database connection profiles
- Log routing decisions
- Handle connection and query errors

## Technology Stack

- Python
- SQL
- SQLAlchemy
- SQLite for local testing
- Optional PostgreSQL or MySQL support

## Project Structure

```text
SQLQuery-Router/
├── src/
├── config/
├── tests/
├── examples/
└── README.md
```

## Getting Started

1. Install Python and project dependencies.
2. Configure a local test database.
3. Set up database connection profiles.
4. Run the query classification examples.
5. Test routing behavior against a development database.

## Design Principles

- Use parameterized queries for data values.
- Never store database credentials in source code.
- Apply explicit permissions to database connections.
- Do not route queries using string matching alone for production use.

## Roadmap

- [ ] Implement SQL statement classification
- [ ] Add configurable routing rules
- [ ] Add database integration tests
- [ ] Measure routing overhead

## License

MIT License (to be added with the LICENSE file).
