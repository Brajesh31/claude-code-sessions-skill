# Claude Code Sessions

A session intelligence skill for searching, reviewing, analyzing, and managing Claude Code session history.

## Capabilities

- Search past sessions by keywords and context.
- Review token usage, model distribution, and tool activity.
- List sessions and inspect detailed session timelines.
- Compare sessions, identify pending tasks, and generate context for resuming work.
- Export transcripts and identify stale or removable session data.
- Use the accompanying local dashboard where configured.

## Data and operation

The skill works with Claude Code's locally stored JSONL session records, typically under `~/.claude/projects/`. Session content can contain source code, prompts, tool output, and other private project information. Keep access local and avoid sharing exported transcripts without reviewing them.

Most analysis operations are read-only. Cleanup and deletion operations are destructive and should only be run after checking the selected files and confirming that they are no longer needed.

## Usage

Use this skill when you need to find an earlier Claude Code discussion, understand usage patterns, recover context, or review outstanding tasks across sessions. Follow the installation and command instructions in `SKILL.md`.
