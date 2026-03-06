# LCARS Sound Pack

A Star Trek: The Next Generation LCARS-themed sound pack for [peon-ping](https://github.com/PeonPing/peon-ping) / [OpenPeon](https://openpeon.com) (CESP 1.0).

## What is OpenPeon?

[OpenPeon](https://openpeon.com) is an open standard for coding event sounds. It works with Claude Code, Codex, Cursor, Windsurf, and other agentic IDEs — giving you audio feedback as your AI agent works. Sound packs follow the [CESP v1.0 spec](https://openpeon.com/spec) and can be browsed on the [OpenPeon registry](https://openpeon.com).

Want to create your own? Check out the [sound pack creation guide](https://openpeon.com/create).

## Sounds

50 sound effects across 7 event categories:

| Event | Sounds | Description |
|---|---|---|
| `session.start` | 3 | Session initialization |
| `task.acknowledge` | 16 | Task accepted and processing |
| `task.complete` | 7 | Task finished successfully |
| `task.error` | 6 | Something failed |
| `input.required` | 11 | Waiting for user input |
| `resource.limit` | 4 | Rate or quota limit hit |
| `user.spam` | 3 | Too many commands too fast |

## Installation

```bash
peon install heidilux/openpeon-lcars
```

Or clone manually:

```bash
git clone https://github.com/heidilux/openpeon-lcars.git
```

## License

Personal use. See `openpeon.json` for details.
