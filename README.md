# Belay

Belay helps Claude Code and Codex learn from prior work. It reconstructs local
agent sessions, shows what keeps going wrong, debriefs how each session was
driven, and carries reviewed guidance into future sessions.

Belay runs locally. Transcript content stays on the developer's machine.

## Install

Belay currently supports Apple Silicon Macs.

```sh
curl -fsSL https://getbelay.vercel.app/install | bash
```

The alpha build is unsigned and unnotarized. The installer verifies release
and package checksums before installation.

## What you get

- A local view of Claude Code and Codex sessions
- Evidence-backed recurring issues and cost estimates
- Per-session Habits debriefs written through your configured agent
- Mission Packs that bring reviewed lessons into the next session
- Local MCP tools for agents to inspect Belay evidence

## Privacy

- Session content is stored encrypted on the local machine.
- Belay does not upload transcript content.
- Optional de-identified usage telemetry can be disabled with
  `belay telemetry off`.
- Release checks can be disabled with `belay updates off`.

## Releases and support

This repository is Belay's public distribution and support surface. It hosts
installation instructions, release binaries, checksums, release notes, and
public issue tracking. Product implementation is maintained separately during
the alpha.

For a bug or product request, open an issue and exclude private source code,
credentials, transcripts, or company-confidential information.

## Useful commands

```sh
belay quickstart
belay doctor
belay version
belay telemetry status
belay updates status
```

Learn more at https://getbelay.vercel.app.
