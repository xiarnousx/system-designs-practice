# System Designs Practice

A personal knowledge base for practicing and internalizing system design concepts.
This repo tracks notes, Q&A-style walkthroughs, and exercises worked through while
studying system design material — currently centered on *Designing Data-Intensive
Applications* (DDIA), with room to grow into other topics (scalability patterns,
distributed systems, real-world architecture case studies, etc.).

## Purpose

- Reinforce system design concepts through active recall (question/answer notes).
- Keep a durable, searchable record of what's been studied chapter by chapter or topic by topic.
- Serve as a reference to revisit before interviews or design discussions.

## Folder Structure

```
system-designs-practice/
├── README.md
├── .gitignore
└── designing-data-intensive-applications/
    ├── chapter-2-nonfunctional-requirements.md
    ├── chapter-3-data-models-and-query-languages.md
    ├── chapter-4-storage-and-retrieval.md
    ├── chapter-5-encoding-and-evolution.md
    ├── chapter-6-replication.md
    ├── chapter-7-sharding.md
    ├── chapter-8-transactions.md
    └── chapter-9-the-trouble-with-distributed-systems.md
```

New topics get their own top-level folder (e.g. `system-design-interviews/`,
`distributed-systems-patterns/`), following the same pattern: one folder per
book/topic, one file per chapter/subtopic.
