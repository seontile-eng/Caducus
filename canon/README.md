# Canon Source of Truth

Everything in this folder is canonical worldbuilding source.

## Conventions

- One concept per file.
- Use lowercase-hyphen filenames (e.g., `silver-city.md`).
- Include YAML frontmatter at top of each file.
- Prefer internal wiki-style links where possible.
- Keep chronology in `canon/timelines/` for global consistency.

## Required Frontmatter Fields

```yaml
id: unique-stable-id
name: Display Name
type: entity|location|faction|system|timeline|glossary
status: draft|canon|deprecated
tags: [tag-a, tag-b]
updated: YYYY-MM-DD
```
