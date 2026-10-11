# SnowSky1

I build tools for AI agents with TypeScript, Python, and Windows automation.
My work includes agent integrations, session reliability, image-generation tooling,
and reproducible fixes in existing codebases.

**[个人展示 · Agent 与 AI](http://122.51.52.78/)**  
Technical notes, personal projects, and an interactive timeline.

<a href="http://122.51.52.78/">
  <img src="assets/agent-ai-showcase.png" alt="Agent 与 AI：蝴蝶时间切片交互展示页，点击访问" width="800">
</a>

*Live-site preview captured on October 11, 2026. Click the image to explore.*

## Selected open-source contributions

Four pull requests authored by me have been merged into
[OpenClaw](https://github.com/openclaw/openclaw):

| Contribution | Merged PR |
| --- | --- |
| Migrate legacy bundled-plugin load paths | [#55054](https://github.com/openclaw/openclaw/pull/55054) |
| Handle malformed Windows execution paths without a drive letter | [#58040](https://github.com/openclaw/openclaw/pull/58040) |
| Respect the selected memory slot in dreaming configuration | [#62275](https://github.com/openclaw/openclaw/pull/62275) |
| Preserve announcement thread IDs during session-list fallback | [#63506](https://github.com/openclaw/openclaw/pull/63506) |

I also received
[co-author credit](https://github.com/openclaw/openclaw/commit/a03b4af0dfa527ec9da6e0a200d852ac8760b0a7)
on the merged [Ollama thinking-control fix, #53200](https://github.com/openclaw/openclaw/pull/53200),
which built on my earlier work.

My ongoing MCP TypeScript SDK work concerns exact `Accept` media-type validation:
[main implementation #2481](https://github.com/modelcontextprotocol/typescript-sdk/pull/2481)
and [v1 backport draft #2738](https://github.com/modelcontextprotocol/typescript-sdk/pull/2738).
These contributions are awaiting maintainer review.

## Projects

### [Universal ImageGen Agent](https://github.com/SnowSky1/universal-imagegen-agent)

A Node.js/Python CLI and library for image-generation workflows, configurable
OpenAI-compatible providers, and installable agent skills. Published on
[npm](https://www.npmjs.com/package/universal-imagegen-agent), with automated tests
and documented upstream attribution.

### [Claude Session Restore](https://github.com/SnowSky1/claude-session-restore)

A Windows utility that snapshots open Claude Code sessions and reopens their
conversations in Windows Terminal tabs.

### [Restaurant Report Agent](https://github.com/SnowSky1/restaurant-report-agent)

A FastAPI, LangGraph, and Next.js workspace for restaurant-site comparisons.
It distinguishes observed data from simulated scenarios and keeps business
assumptions visible in its reports.

## How I work

- Reproduce a reported behavior before changing it.
- Keep implementation scope and regression coverage explicit.
- Use AI-assisted development while checking the resulting code and behavior.
- Document what was tested and what still needs real-environment verification.

For a project question or bug report, please open an issue in the relevant
repository. For a tour of my work, visit **[Agent 与 AI](http://122.51.52.78/)**.
