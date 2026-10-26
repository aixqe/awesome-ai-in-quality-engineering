# Awesome AI in Quality Engineering

A curated list of AI tools, frameworks, research, and methods that matter for modern software quality engineering. No hype — just what each one does, so you can evaluate it for your own stack.

## AI-native test tools

Tools built around AI from the start: they generate, execute, and maintain tests with minimal scripting.

- [ACCELQ](https://www.accelq.com) — Agentic no-code test automation across web, API, mobile, desktop, SAP, and Salesforce.
- [Virtuoso](https://www.virtuosoqa.com) — Natural-language test authoring; tests are AI-maintained and self-healing.
- [Mabl](https://www.mabl.com) — Intelligent test automation with auto-healing and ML-assisted failure diagnostics.
- [testRigor](https://www.testrigor.com) — Plain-English test creation aimed at manual testers; no code required.
- [Testsigma](https://www.testsigma.com) — AI-assisted test automation for web, mobile, API, and desktop applications.
- [Momentic](https://www.momentic.ai) — Intent-based testing with self-healing locators; describe what to test, not how.
- [TestDriver](https://www.testdriver.ai) — Computer-use AI agent that tests by reading screens visually, extending past the browser to desktop apps.
- [QA Wolf](https://www.qawolf.com) — Emits deterministic, human-readable Playwright/Appium code; self-healing that fixes the test code, not just runtime behavior.
- [Test-Lab](https://www.test-lab.ai) — Plain-English test plans executed by an AI browser agent; exports the Playwright scripts so you own the artifacts.

## AI-augmented tools

AI layered onto human-authored automation — for teams with existing Selenium/Playwright estates to preserve.

- [Tricentis Testim](https://www.tricentis.com) — Smart Locators and AI-stabilized automation; agentic automation for Salesforce.
- [LambdaTest KaneAI](https://www.lambdatest.com) — Conversational test authoring on a real-device cloud grid.

## Visual AI testing

- [Applitools](https://www.applitools.com) — Visual AI that distinguishes real UI bugs from harmless layout shifts.

## Frameworks & open source

The open building blocks — auditable, version-controlled, and yours to keep.

- [Playwright](https://playwright.dev) — Reliable end-to-end testing across Chromium, Firefox, and WebKit with a single API.
- [Selenium](https://www.selenium.dev) — The long-standing open standard for browser automation.
- [Aider](https://aider.chat) — Open-source AI pair programming in the terminal.
- [Cline](https://cline.bot) — Open-source autonomous coding agent for VS Code with plan/act approval gates.
- [OpenHands](https://www.all-hands.dev) — Open-source platform for AI software-development agents.

## Research & reports

The data behind the claims. Read these before believing a vendor benchmark.

- [World Quality Report 2025](https://www.capgemini.com) (Capgemini, Sogeti, OpenText) — Annual industry survey; the anchor dataset on GenAI adoption in QE (~90% of orgs pursuing, 15% scaled).
- [DORA](https://dora.dev) (Google Cloud) — DevOps research program; tracks how AI adoption affects deploy frequency and maintenance load.
- [PractiTest — State of Testing](https://www.practitest.com) — Annual practitioner survey; tracks real-world AI use in test design (70% of testers used AI for test creation in 2026).

## Spec-driven development

Writing the spec first, then letting agents implement against it — the workflow that keeps AI-generated code honest.

- [Kiro](https://kiro.dev) — Amazon's spec-driven development environment (formerly Amazon Q Developer).
- [obra/superpowers](https://github.com/obra/superpowers) — Open-source methodology layer that forces coding agents through spec-writing and TDD phases before implementation.
- [Spec Kit](https://github.com/github/spec-kit) — GitHub's open-source spec-driven toolkit: constitution → spec → plan → tasks → implement, with any AI coding agent.
- [OpenSpec](https://github.com/Fission-AI/OpenSpec) — Lightweight, brownfield-first spec-driven framework; each change is a delta spec (ADDED / MODIFIED / REMOVED) against current behaviour.
- [Spec-Driven Development with Coding Agents](https://www.deeplearning.ai/courses/spec-driven-development-with-coding-agents) (DeepLearning.AI × JetBrains, course) — the short course behind Edition 2.

---

## Contributing

Found a tool, framework, or report that belongs here? Open a PR or issue with the name, link, and a one-line factual description. Entries must be real, maintained, and relevant to AI in quality engineering — marketing copy gets edited down.
