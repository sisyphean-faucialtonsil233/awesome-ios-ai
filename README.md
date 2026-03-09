# Awesome iOS AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> AI agent skills, agent teams, MCP servers, and tools that make AI coding assistants better at Swift and iOS development.

Your AI coding tools write Swift like it is 2020. They use `ObservableObject` when `@Observable` exists. They ignore actor isolation. They produce views with no accessibility modifiers. They have never heard of Apple Foundation Models.

**Skills and agent teams fix that.** They give GitHub Copilot, Claude Code, Cursor, and Codex expert-level Swift and iOS knowledge on demand — so your AI writes modern, accessible, concurrent Swift the way it should be written.

We started this list while building the Swift Agent Team and realized no central resource existed for any of this. The skills listed here help us every day. This is a community effort — contributions welcome.

## Contents

- [What Are Skills](#what-are-skills)
- [How to Install](#how-to-install)
- [Skills](#skills)
  - [SwiftUI](#swiftui)
  - [Swift Concurrency](#swift-concurrency)
  - [Testing](#testing)
  - [Debugging](#debugging)
  - [Design and Platform](#design-and-platform)
  - [Workflow and Automation](#workflow-and-automation)
  - [Accessibility](#accessibility)
- [Agent Teams](#agent-teams)
- [MCP Servers](#mcp-servers)
- [Notable Authors](#notable-authors)
- [Resources](#resources)

## What Are Skills

[Agent Skills](https://agentskills.io/) are an open standard for giving AI coding agents specialized knowledge. A skill is a folder containing instructions, reference docs, and scripts that an agent loads on demand when it detects a relevant task.

Skills work across multiple tools — GitHub Copilot, Claude Code, Cursor, Codex, and many more.

## How to Install

Install any skill with a single command using the [skills CLI](https://skills.sh/docs/cli):

```bash
# Install a single skill globally (available in all projects)
npx skills add <owner/repo@skill-name> -g -y

# Install ALL skills from an author's repo at once
npx skills add <owner/repo> --all

# Search for skills
npx skills find swift
npx skills find swiftui
npx skills find ios
```

Browse all skills at **[skills.sh](https://skills.sh/?q=swift)**.

### Install Everything

Want the full iOS AI skill stack? Run these three commands to install all skills from the top authors:

```bash
# All skills from Antoine van der Lee (SwiftUI Expert, Concurrency, Testing)
npx skills add avdlee/swiftui-agent-skill --all
npx skills add avdlee/swift-concurrency-agent-skill --all
npx skills add avdlee/swift-testing-agent-skill --all

# All 10 skills from Thomas Ricouard (Performance, Liquid Glass, View Refactor, Debugger, and more)
npx skills add dimillian/skills --all

# SwiftUI Pro from Paul Hudson
npx skills add twostraws/swiftui-agent-skill --all
```

The `--all` flag installs every skill in the repo globally with no prompts.

### One-Command Install (Everything)

Install every skill from this list with a single command:

```bash
curl -fsSL https://raw.githubusercontent.com/techopolis-group/awesome-ios-ai/main/install.sh | bash
```

Or clone and run locally:

```bash
git clone https://github.com/techopolis-group/awesome-ios-ai.git
cd awesome-ios-ai
./install.sh
```

This installs all skills from Antoine van der Lee, Thomas Ricouard, and Paul Hudson — the complete iOS AI skill stack.

---

## Skills

### SwiftUI

- [SwiftUI Expert](https://skills.sh/avdlee/swiftui-agent-skill/swiftui-expert-skill) - State management, view composition, performance, iOS 26+ Liquid Glass. By Antoine van der Lee.
- [SwiftUI Pro](https://skills.sh/twostraws/swiftui-agent-skill/swiftui-pro) - Modern APIs, accessibility, data flow, navigation, and performance. By Paul Hudson.
- [SwiftUI Performance Audit](https://skills.sh/dimillian/skills/swiftui-performance-audit) - Diagnose slow rendering, janky scrolling, excessive view updates, and layout thrash. By Thomas Ricouard.
- [SwiftUI View Refactor](https://skills.sh/dimillian/skills/swiftui-view-refactor) - Consistent view structure, MV patterns, @Observable usage, dependency injection. By Thomas Ricouard.
- [SwiftUI UI Patterns](https://skills.sh/dimillian/skills/swiftui-ui-patterns) - Component references for TabView, NavigationStack, Sheets, and view composition. By Thomas Ricouard.
- [SwiftUI Liquid Glass](https://skills.sh/dimillian/skills/swiftui-liquid-glass) - iOS 26+ Liquid Glass API with `glassEffect`, `GlassEffectContainer`, and availability fallbacks. By Thomas Ricouard.

### Swift Concurrency

- [Swift Concurrency](https://skills.sh/avdlee/swift-concurrency-agent-skill/swift-concurrency) - Async/await, actors, Sendable, and strict concurrency. By Antoine van der Lee.
- [Swift Concurrency Expert](https://skills.sh/dimillian/skills/swift-concurrency-expert) - Swift 6.2+ focused. Actor isolation, data-race safety, minimal-change fixes for compiler errors. By Thomas Ricouard.

### Testing

- [Swift Testing Expert](https://skills.sh/avdlee/swift-testing-agent-skill/swift-testing-expert) - Modern Swift Testing framework with `#expect`, `#require`, traits, tags, parameterized tests, and XCTest migration. By Antoine van der Lee.

### Debugging

- [iOS Debugger Agent](https://skills.sh/dimillian/skills/ios-debugger-agent) - Build, run, and debug iOS apps on simulators via XcodeBuildMCP. By Thomas Ricouard.

### Design and Platform

- [iOS HIG](https://skills.sh/johnrogers/claude-swift-engineering/ios-hig) - Apple Human Interface Guidelines compliance. By johnrogers.
- [iOS 26 Platform](https://skills.sh/johnrogers/claude-swift-engineering/ios-26-platform) - Platform APIs and patterns for iOS 26. By johnrogers.
- [Mobile iOS Design](https://skills.sh/wshobson/agents/mobile-ios-design) - iOS design patterns and architecture. By wshobson.

### Workflow and Automation

- [App Store Changelog](https://github.com/Dimillian/Skills/tree/main/app-store-changelog) - Generate App Store release notes from Git history. By Thomas Ricouard.
- [GH Issue Fix Flow](https://github.com/Dimillian/Skills/tree/main/github) - End-to-end GitHub issue resolution with read, fix, build, test, and push. By Thomas Ricouard.
- [macOS SwiftPM Packaging](https://github.com/Dimillian/Skills/tree/main/macos-spm-app-packaging) - Scaffold, build, and package SwiftPM macOS apps without Xcode. By Thomas Ricouard.
- [Swift MCP Server Generator](https://skills.sh/github/awesome-copilot/swift-mcp-server-generator) - Generate MCP servers in Swift. By GitHub.

### Accessibility

- [iOS Accessibility](https://skills.sh/dpearson2699/swift-ios-skills/ios-accessibility) - Accessibility patterns and VoiceOver support for iOS. By dpearson2699.
- [Swift Accessibility](https://skills.sh/madebyecho/agent-skills/swift-accessibility) - Accessibility guidance for Swift apps. By madebyecho.

The SwiftUI Pro and SwiftUI Expert skills listed above also include accessibility coverage.

---

## Agent Teams

Skills give agents knowledge. Agent teams take it further with coordinated specialists and an orchestrator that routes tasks to the right expert automatically. If you have built an agent team for iOS or Swift development, submit it.

- [Swift Agent Team](https://github.com/techopolis-group/swift-agent-team) - 16 orchestrated specialists covering concurrency, SwiftUI, accessibility, security, testing, StoreKit, SwiftData, visionOS, Core ML, MLX, and Foundation Models. Works with Claude Code and VS Code Copilot.

---

## MCP Servers

MCP (Model Context Protocol) servers give AI agents access to external tools and data sources.

- [XcodeBuildMCP](https://github.com/nicklama/xcode-build-mcp) - Build, run, and test Xcode projects from AI agents.
- [Sosumi MCP](https://github.com/kanaa257/sosumi.ai) - Access Apple developer documentation from AI agents.
- [awesome-copilot MCP](https://github.com/github/awesome-copilot) - Search and install agents, skills, and instructions from GitHub.

---

## Notable Authors

- [Antoine van der Lee](https://github.com/AvdLee) - Author of SwiftLee. Maintains the top-installed Swift skills across SwiftUI, Concurrency, Testing, and Core Data.
- [Thomas Ricouard](https://github.com/Dimillian) - Creator of IceCubes. His Skills repo is the most comprehensive iOS-specific skills collection with 10 skills.
- [Paul Hudson](https://github.com/twostraws) - Creator of Hacking with Swift. His SwiftUI Pro skill brings comprehensive reference docs to AI agents.

---

## Resources

- [skills.sh](https://skills.sh) - Searchable directory of all agent skills with install counts and security audits.
- [Agent Skills Specification](https://agentskills.io/specification) - The open standard for building skills.
- [VS Code Copilot Customization](https://code.visualstudio.com/docs/copilot/copilot-customization) - Official guide for workspace instructions, agents, prompts, hooks, and skills.

---

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

**Skill authors:** Submit your iOS and Swift skills. See the contributing guide for requirements.

**Agent team authors:** Built an agent team for Swift development? Add it to the Agent Teams section.

---

## Footnotes

Created by [Taylor Arndt](https://github.com/taylorarndt). Maintained by [Techopolis](https://github.com/techopolis-group).
