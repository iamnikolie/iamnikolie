# Mykola Klitovchenko

Warsaw, Poland. I build tools I actually use — small, single-purpose CLIs for the
parts of the day software should be handling instead of me.

Lately that means command-line interfaces built for agents rather than for humans
only. A CLI an agent runs from Bash beats an MCP server for anything it needs
often: the output is plain text it can read, and nothing costs context until it
is called.

### Tools

#### Running agents

- **[zmina](https://github.com/iamnikolie/zmina)** — a shift of Claude Code
  agents: long-lived role sessions in tmux (a designer, developer seats, whatever
  you name) and one dispatcher that never sleeps. It routes work to roles, keeps
  a task ledger with a git worktree per code task, and watches their health.
- **[oko](https://github.com/iamnikolie/oko)** — a browser for agents: a
  dedicated Chrome driven over CDP, one shell call per action. Pages as
  markdown, element refs for clicks and forms, what changed after each action,
  console and network errors, screenshots and recordings.
- **[mcpcli](https://github.com/iamnikolie/mcpcli)** — any remote MCP server as
  a CLI: OAuth profiles per account, `key=value` tool calls, one HTTP round trip
  per call, a generated skill file instead of schemas in every session.
- **[svidoq](https://github.com/iamnikolie/svidoq)** — read-only SQL for agents:
  a parsed allowlist and a read-only transaction, capped results, credentials
  that never reach the transcript.

#### Web research

- **[exa-cli](https://github.com/iamnikolie/exa-cli)** — Exa web search from the
  terminal: search, page contents, grounded answers and agent runs.
- **[parallel-cli](https://github.com/iamnikolie/parallel-cli)** — Parallel web
  research from the terminal: search, page extraction, cited answers, research
  tasks with per-field citations, batch enrichment, entity lists and monitors.
  Twin of exa-cli, with a side-by-side comparison.

#### Team tools

- **[gitlab-cli](https://github.com/iamnikolie/gitlab-cli)** — GitLab from the
  terminal: merge requests, pipelines, repo objects, token-lean output.
- **[slack-cli](https://github.com/iamnikolie/slack-cli)** — Slack from the
  terminal: transcripts, search, posting and files.
- **[fibery-cli](https://github.com/iamnikolie/fibery-cli)** — Fibery from the
  terminal: query, create, comment, attach files.
- **[oolog](https://github.com/iamnikolie/oolog)** — OpenObserve logs from the
  terminal (it ships no CLI of its own): tail, search, histograms, top values,
  context around a line, raw SQL, with an SSH tunnel built in.

#### Media

- **[gengoya](https://github.com/iamnikolie/gengoya)** — generate images, video,
  music and speech from the terminal: OpenAI and Gemini images, Veo and Gemini
  Omni video, Lyria songs, Gemini TTS. Prints file paths, estimates cost first.
- **[dziga](https://github.com/iamnikolie/dziga)** — turn a video into context an
  LLM can actually read. ffmpeg contact sheets and stills locally, Gemini for what
  stills cannot show.

#### Your own data

- **[llmspend](https://github.com/iamnikolie/llmspend)** — what your OpenAI and
  Anthropic orgs used and spent, read-only with admin keys: usage of every kind,
  billed cost, spend limits, which key belongs to which project and org.
- **[wispr-cli](https://github.com/iamnikolie/wispr-cli)** — your Wispr Flow
  dictations, meeting notes and transcripts from the local database, read-only,
  exported as Markdown for a vault.

Go, MIT, no telemetry.
