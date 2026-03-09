# Awesome iOS AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Making AI coding assistants experts at Swift and iOS development.

AI coding tools write Swift like it is 2020. They use `ObservableObject` when `@Observable` exists. They ignore actor isolation. They produce views with no accessibility modifiers. Skills, agents, and MCP servers fix that by giving AI assistants expert-level Swift knowledge on demand.

## Contents

- [Skills](#skills)
- [Agents](#agents)
- [MCP Servers](#mcp-servers)
- [Resources](#resources)

## Skills

[Agent Skills](https://agentskills.io/) are an open standard for giving AI coding agents specialized knowledge. Skills work across GitHub Copilot, Claude Code, Cursor, Codex, and more. Install any skill with the [skills CLI](https://skills.sh/docs/cli): `npx skills add <owner/repo@skill-name> -g -y`

### SwiftUI

- [SwiftUI Expert](https://skills.sh/avdlee/swiftui-agent-skill/swiftui-expert-skill) - State management, view composition, performance, and iOS 26+ Liquid Glass.
- [SwiftUI Pro](https://skills.sh/twostraws/swiftui-agent-skill/swiftui-pro) - Modern APIs, accessibility, data flow, navigation, and performance.
- [SwiftUI Performance Audit](https://skills.sh/dimillian/skills/swiftui-performance-audit) - Diagnose slow rendering, janky scrolling, excessive view updates, and layout thrash.
- [SwiftUI View Refactor](https://skills.sh/dimillian/skills/swiftui-view-refactor) - Consistent view structure, MV patterns, @Observable usage, and dependency injection.
- [SwiftUI UI Patterns](https://skills.sh/dimillian/skills/swiftui-ui-patterns) - Component references for TabView, NavigationStack, Sheets, and view composition.
- [SwiftUI Liquid Glass](https://skills.sh/dimillian/skills/swiftui-liquid-glass) - iOS 26+ Liquid Glass API with `glassEffect`, `GlassEffectContainer`, and availability fallbacks.

### Swift Concurrency

- [Swift Concurrency](https://skills.sh/avdlee/swift-concurrency-agent-skill/swift-concurrency) - Async/await, actors, Sendable, and strict concurrency for Swift 6.
- [Swift Concurrency Expert](https://skills.sh/dimillian/skills/swift-concurrency-expert) - Swift 6.2+ actor isolation, data-race safety, and minimal-change fixes for compiler errors.

### Testing

- [Swift Testing Expert](https://skills.sh/avdlee/swift-testing-agent-skill/swift-testing-expert) - Modern Swift Testing framework with `#expect`, `#require`, traits, tags, parameterized tests, and XCTest migration.

### Debugging

- [iOS Debugger Agent](https://skills.sh/dimillian/skills/ios-debugger-agent) - Build, run, and debug iOS apps on simulators via XcodeBuildMCP.

### Design and Platform

- [iOS HIG](https://skills.sh/johnrogers/claude-swift-engineering/ios-hig) - Apple Human Interface Guidelines compliance checks.
- [iOS 26 Platform](https://skills.sh/johnrogers/claude-swift-engineering/ios-26-platform) - Platform APIs and patterns for iOS 26.
- [Mobile iOS Design](https://skills.sh/wshobson/agents/mobile-ios-design) - iOS design patterns and architecture guidance.

### Workflow and Automation

- [App Store Changelog](https://github.com/Dimillian/Skills/tree/main/app-store-changelog) - Generate App Store release notes from Git history.
- [GH Issue Fix Flow](https://github.com/Dimillian/Skills/tree/main/github) - End-to-end GitHub issue resolution with read, fix, build, test, and push.
- [macOS SwiftPM Packaging](https://github.com/Dimillian/Skills/tree/main/macos-spm-app-packaging) - Scaffold, build, and package SwiftPM macOS apps without Xcode.
- [Swift MCP Server Generator](https://skills.sh/github/awesome-copilot/swift-mcp-server-generator) - Generate MCP servers in Swift.

### Accessibility

- [iOS Accessibility](https://skills.sh/dpearson2699/swift-ios-skills/ios-accessibility) - VoiceOver support, accessibility modifiers, and Dynamic Type patterns for iOS.
- [Swift Accessibility](https://skills.sh/madebyecho/agent-skills/swift-accessibility) - Accessibility guidance and best practices for Swift apps.

## Agents

- [Swift Agents](https://github.com/Techopolis/swift-agents) - Sixteen orchestrated specialists covering concurrency, SwiftUI, accessibility, security, testing, StoreKit, SwiftData, visionOS, Core ML, MLX, and Foundation Models.

## MCP Servers

- [XcodeBuildMCP](https://github.com/nicklama/xcode-build-mcp) - Build, run, and test Xcode projects from AI agents.
- [Sosumi MCP](https://github.com/kanaa257/sosumi.ai) - Access Apple developer documentation from AI agents.
- [awesome-copilot MCP](https://github.com/github/awesome-copilot) - Search and install agents, skills, and MCP servers from GitHub.

## Resources

- [skills.sh](https://skills.sh) - Searchable directory of all agent skills with install counts and security audits.
- [Agent Skills Specification](https://agentskills.io/specification) - The open standard for building agent skills.
- [VS Code Copilot Customization](https://code.visualstudio.com/docs/copilot/copilot-customization) - Official guide for workspace instructions, agents, prompts, hooks, and skills.

## Contributing

Contributions welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR.

## Footnotes

Created by [Taylor Arndt](https://github.com/taylorarndt). Maintained by [Techopolis](https://github.com/Techopolis).
