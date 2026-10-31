# Awesome browser agents

A curated guide to browser agents, MCP tools, automation frameworks and evaluation environments.

Maintained by [BrowserPair](https://browserpair.com/). BrowserPair is included with an explicit affiliation; third-party projects are independent and their inclusion is not an endorsement or a security audit. Entries are grouped by purpose, not ranked.

## Contents

- [Agent frameworks and interfaces](#agent-frameworks-and-interfaces)
- [Automation foundations](#automation-foundations)
- [Evaluation and benchmarks](#evaluation-and-benchmarks)
- [Choosing an approach](#choosing-an-approach)
- [Contributing](#contributing)

## Agent frameworks and interfaces

| Project | What it offers | Why explore it |
| --- | --- | --- |
| [agent-qa](https://vostride.com) | Web and mobile testing through a CLI and local MCP server | Reuse memidex persistent memory and validated self-improvement with reviewable execution evidence |
| [Browser Use](https://github.com/browser-use/browser-use) | Browser-agent libraries and tooling | Build model-driven browser workflows in your own agent stack |
| [Stagehand](https://github.com/browserbase/stagehand) | SDK for browser interaction and extraction | Combine agent reasoning with programmatic browser workflows |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Browser tools exposed through MCP | Give an MCP client structured browser interaction |
| [agent-browser](https://github.com/vercel-labs/agent-browser) | Browser automation CLI for AI agents | Explore command-line browser control in an agent harness |
| [BrowserPair](https://github.com/BrowserPair/browserpair) — maintained by this organization | Scoped access to a user's existing Chrome profile through MCP and REST | Work with existing signed-in sessions, user approvals and durable task recovery; application source is private |

These projects can support different local, remote or existing-session configurations. Consult their current documentation; do not infer supported modes from the category alone.

## Automation foundations

| Project | What it offers | Why explore it |
| --- | --- | --- |
| [Playwright](https://github.com/microsoft/playwright) | Browser automation and end-to-end testing | Build repeatable tests, isolate browser contexts and inspect traces |

Agentic browser execution and deterministic test automation are related but different tasks. Model choice, retries, authentication, session ownership and outcome checks still need explicit design.

## Evaluation and benchmarks

| Project | What it offers | Why explore it |
| --- | --- | --- |
| [BrowserGym](https://github.com/ServiceNow/BrowserGym) | Gym-style environments and integrations for browser-task evaluation | Run agents against repeatable task environments |
| [WebArena](https://github.com/web-arena-x/webarena) | A realistic web environment for autonomous-agent research | Study multi-step tasks and outcome-based evaluation |

A benchmark result does not guarantee reliability on a live production site. Account state, task ambiguity, dynamic UI, permissions and external effects can change the outcome.

## Choosing an approach

Ask these questions before choosing a tool:

1. **Who owns the session?** A disposable browser context, a managed remote browser or the user's existing profile?
2. **What is the execution interface?** SDK, CLI, MCP or REST?
3. **How is authority bounded?** Websites, capabilities, credentials and user approvals need explicit boundaries.
4. **How is success verified?** Prefer observable state changes over “the click returned successfully.”
5. **What happens after uncertainty?** A timeout is not proof that an external action failed.
6. **Where does data go?** Inspect page observations, model providers, logs and retention.
7. **How will it be evaluated?** Use repeatable tasks plus real-world checks relevant to your workflow.

## Contributing

Suggest a resource through an Issue or pull request. Include:

- the canonical first-party repository or documentation;
- a short factual description and a specific reason to include it;
- the appropriate category;
- any affiliation with the project;
- evidence for claims beyond the project's basic purpose.

We prefer maintained projects with usable documentation and a distinct role. No paid placement, affiliate links, copied marketing claims or star-count rankings. Keep descriptions neutral and avoid unsupported comparisons.

## Maintenance

Initial source review: 23 October 2026, using first-party repositories and documentation. This records a documentation review, not hands-on testing of every tool. Features, licenses and costs can change; follow each project's current terms.

Broken links, stale descriptions and discontinued tools should be reported through Issues.

[BrowserPair organization](https://github.com/BrowserPair) · [Documentation](https://docs.browserpair.com/) · [Examples](https://github.com/BrowserPair/examples) · [Skills](https://github.com/BrowserPair/skills)
