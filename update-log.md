# Claude Code Guide - Update Log

This file tracks automated updates to the guide.

---

## 2026-01-15: Pipeline Initialized

- Auto-update pipeline created
- Bi-daily cron job configured (every 2 days at 3am UTC)
- Sources monitored:
  - Anthropic Docs
  - GitHub Releases
  - Anthropic News
  - Anthropic Changelog

---

## 2026-07-27: Update

Five-month catch-up bringing the guide from Claude Code v2.1.39 to v2.1.220. Added CLI changelog entries for every substantive release between v2.1.41 and v2.1.220 (skipping releases whose only note was "bug fixes and reliability improvements" or "internal infrastructure improvements", matching prior practice). Added three new sections with Contents entries: Agent View and Background Sessions (claude agents, --bg, attach/logs/stop/rm/respawn/daemon, --json scripting, worktree isolation, keyboard controls), Dynamic Workflows (ultracode trigger keyword, /workflows, workflowSizeGuideline), and Auto Mode (availability timeline, autoMode.* configuration, safety behavior, PermissionDenied hook). Added a Model Lineup section covering Claude Opus 5, Claude Sonnet 5, Claude Fable 5, Opus 4.8, Opus 4.7, and Sonnet 4.6 plus effort levels and org model controls. Updated Fast Mode for its move to Opus 5 and Opus 4.8. Expanded the CLI Flags Reference, the Hook Events table (17 new events plus a hook-configuration additions table), Environment Variables (five new groups), a new Settings Added Since v2.1.39 table, and the Built-in Commands reference. Added a v2.1.41-v2.1.220 Breaking Changes and Renames table. Code fences verified balanced (494, was 476) and all 44 internal anchor links validated.

Sections: [Changelog (CLI Releases), Advanced Features (Model Lineup NEW, Fast Mode), Agent View and Background Sessions (NEW), Dynamic Workflows (NEW), Auto Mode (NEW), Quick Reference (CLI Flags), Hooks System (Hook Events), Environment Variables, New Settings, Built-in Commands, Breaking Changes, Contents, This Guide's Changelog, update-log.md]

---

*Updates are logged automatically by the pipeline script.*
