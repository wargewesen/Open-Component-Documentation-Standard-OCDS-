# Contributing

Thanks for your interest in contributing to the Open Component Documentation Standard (OCDS). This project aims to define an open, AI-readable, cross-framework standard for component documentation and metadata.

## Code of Conduct
Be respectful, assume good intent, and focus on constructive collaboration. Harassment, discrimination, or hostile behavior is not tolerated.

## Ways to Contribute
You can contribute in any of these ways:

- **Use cases**: describe real component documentation problems you want the standard to solve.
- **Examples**: share (sanitized) component docs or patterns from your design system.
- **Spec text**: propose definitions, terms, and normative requirements (MUST/SHOULD/MAY).
- **Schema feedback**: propose fields, data types, and validation rules.
- **Tooling**: prototypes, converters, linters, or reference implementations.
- **Accessibility**: review and propose accessible defaults and required metadata.

## Where Work Happens
- **Discussions**: early ideas, proposals, questions, and use cases
- **Issues**: track specific work items and decisions
- **Pull Requests**: spec edits, schema updates, examples, tooling

## Getting Started
1. Read the README and the current draft in `spec/`.
2. Check `issues` for “good first issue” or “help wanted”.
3. If proposing a new concept, open a **Discussion** first.

## Proposing Changes (RFC-lite)
For changes that affect the data model or compatibility:
1. Open a Discussion titled: `Proposal: <short name>`
2. Include:
   - Problem statement
   - Proposed solution
   - Example JSON (before/after)
   - Compatibility & migration notes
   - Open questions
3. Once there is rough agreement, open a PR.

## Pull Request Guidelines
- Keep PRs focused and small when possible.
- Link to a related Issue/Discussion.
- Include updated examples if you change the schema.
- Prefer adding fields as optional first; avoid breaking changes.
- Use normative keywords in spec text: **MUST**, **SHOULD**, **MAY** (RFC 2119 style).

## Spec Style Guide
- Use clear definitions and avoid framework-specific language unless in a mapping section.
- Separate:
  - **Core model** (framework-agnostic)
  - **Bindings** (framework-specific mappings)
  - **Examples** (realistic, minimal)
- When you add a field, document:
  - Meaning
  - Type
  - Whether required
  - Defaults
  - Validation rules

## Accessibility Requirements
Accessibility is not optional. When adding/altering component semantics, include:
- Roles/ARIA expectations (where applicable)
- Keyboard interaction expectations
- Focus management rules
- Color contrast and token guidance (when relevant)

## License
By contributing, you agree that your contributions will be licensed under the repository’s license.

## Security / Sensitive Information
Do not include proprietary system details, internal URLs, customer names, or restricted content. Sanitize examples and remove identifiers.

## Questions
If you’re unsure where something belongs, open a Discussion and we’ll help route it.
