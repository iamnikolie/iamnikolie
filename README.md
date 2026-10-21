# Mykola Klitovchenko

Warsaw, Poland. I build tools I actually use — small, single-purpose CLIs for the
parts of the day software should be handling instead of me.

Lately that means command-line interfaces built for agents rather than for humans
only. A CLI an agent runs from Bash beats an MCP server for anything it needs
often: the output is plain text it can read, and nothing costs context until it
is called.

### Tools

- **[dziga](https://github.com/iamnikolie/dziga)** — turn a video into context an
  LLM can actually read. ffmpeg contact sheets and stills locally, Gemini for what
  stills cannot show.
- **[exa-cli](https://github.com/iamnikolie/exa-cli)** — Exa web search from the
  terminal: search, page contents, grounded answers and agent runs.
- **[fibery-cli](https://github.com/iamnikolie/fibery-cli)** — Fibery from the
  terminal: query, create, comment, attach files.
- **[gengoya](https://github.com/iamnikolie/gengoya)** — generate images, video,
  music and speech from the terminal: OpenAI and Gemini images, Veo and Gemini
  Omni video, Lyria songs, Gemini TTS. Prints file paths, estimates cost first.
- **[gitlab-cli](https://github.com/iamnikolie/gitlab-cli)** — GitLab from the
  terminal: merge requests, pipelines, repo objects, token-lean output.
- **[mcpcli](https://github.com/iamnikolie/mcpcli)** — any remote MCP server as
  a CLI: OAuth profiles per account, `key=value` tool calls, one HTTP round trip
  per call, a generated skill file instead of schemas in every session.
- **[oko](https://github.com/iamnikolie/oko)** — a browser for agents: a
  dedicated Chrome driven over CDP, one shell call per action. Pages as
  markdown, element refs for clicks and forms, what changed after each action,
  console and network errors, screenshots and recordings.
- **[oolog](https://github.com/iamnikolie/oolog)** — OpenObserve logs from the
  terminal (it ships no CLI of its own): tail, search, histograms, top values,
  context around a line, raw SQL, with an SSH tunnel built in.
- **[parallel-cli](https://github.com/iamnikolie/parallel-cli)** — Parallel web
  research from the terminal: search, page extraction, cited answers, research
  tasks with per-field citations, batch enrichment, entity lists and monitors.
  Twin of exa-cli, with a side-by-side comparison.
- **[slack-cli](https://github.com/iamnikolie/slack-cli)** — Slack from the
  terminal: transcripts, search, posting and files.
- **[svidoq](https://github.com/iamnikolie/svidoq)** — read-only SQL for agents:
  a parsed allowlist and a read-only transaction, capped results, credentials
  that never reach the transcript.
- **[wispr-cli](https://github.com/iamnikolie/wispr-cli)** — your Wispr Flow
  dictations, meeting notes and transcripts from the local database, read-only,
  exported as Markdown for a vault.

Go, MIT, no telemetry.
