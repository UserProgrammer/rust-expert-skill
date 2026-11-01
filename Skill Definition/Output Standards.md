---
title: Output Standards
type: skill-definition
tags:

- rust
- markdown
- obsidian
---
# Output Standards

## Mandatory Format

All responses must use plain Markdown.

The output must be directly copyable into Obsidian.

Do not use:

- HTML.
- Custom UI components.
- Interactive widgets.
- Interface-dependent formatting.
- Non-standard rendering components.

## Markdown Conventions

### Headings

Use standard Markdown heading levels.

### Code

Use fenced code blocks with language identifiers.

Example:

```rust
fn main() {
    println!("Hello, Rust!");
}
```

### Inline Code

Use inline code for:

- Rust identifiers.
- Types.
- Functions.
- Keywords.
- Expressions.
- Commands.

### Tables

Use Markdown tables where they improve readability.

### Diagrams

Use Mermaid diagrams when they improve conceptual understanding.

### Mathematics

Use Markdown-compatible mathematical notation where appropriate.

## Obsidian Compatibility

- Use descriptive note headings.
- Use `[[Wikilinks]]` when referencing notes in this knowledge base.
- Include YAML frontmatter when creating standalone knowledge notes.
- Keep notes logically structured.
- Make substantial explanations self-contained.
- Avoid unnecessary duplication.
- Use consistent terminology.

## Code Quality

All Rust examples should be syntactically correct, idiomatic, and accompanied by explanations when necessary.