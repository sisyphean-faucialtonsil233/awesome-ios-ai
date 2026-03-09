# Contributing to Awesome iOS AI

Thanks for contributing. This list is community-maintained and curated. We accept skills, agents, and MCP servers that make AI coding assistants better at Swift and iOS development.

## Adding an Entry

### Requirements

Your entry must:

1. **Target iOS, Swift, or SwiftUI specifically.** General-purpose tools do not belong here.
2. **Be publicly available.** Installable via `npx skills add` or from a public GitHub repo.
3. **Actually work.** We test entries before merging.
4. **Not duplicate an existing entry.**

### Format

Follow the existing entry format exactly:

```
- [Name](url) - Description starting with uppercase, ending with a period.
```

The description should be objective, not a tagline or marketing blurb.

### How to Submit

1. Fork this repository.
2. Add your entry to the bottom of the appropriate category in `README.md`.
3. Submit a PR with a clear description of what you are adding and why it belongs.

### Choosing a Category

| Category | What belongs here |
|----------|-------------------|
| SwiftUI | View composition, state management, performance, UI patterns |
| Swift Concurrency | Async/await, actors, Sendable, data-race safety |
| Testing | Swift Testing, XCTest, test patterns |
| Debugging | Simulator, Xcode build, runtime inspection |
| Design and Platform | HIG, platform APIs, design patterns, architecture |
| Workflow and Automation | Release notes, issue workflows, CI/CD, packaging |
| Accessibility | VoiceOver, Dynamic Type, accessibility traits |
| Agents | Coordinated agent teams for Swift development |
| MCP Servers | External tool integrations for iOS development |

If your entry does not fit an existing category, propose a new one in your PR description.

## Quality Standards

- **Specificity.** Focused tools that do one thing well over broad tools that do many things loosely.
- **Maintained.** No archived, deprecated, or abandoned projects.
- **Documented.** Must have a README or docs explaining what it does.

## What We Do Not Accept

- Tools that are not specific to iOS or Swift development.
- Duplicate submissions of already-listed entries.
- Unmaintained or archived projects.
- Entries without documentation.

## Questions

Open an issue if you are unsure whether your entry fits.
