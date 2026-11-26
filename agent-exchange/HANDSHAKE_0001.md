# Hakinei Agent Exchange v0.1 — Handshake 0001

**Status:** READY_FOR_CODEX
**Task ID:** HAK-EXCHANGE-0001
**Created by:** Chat (project management)
**Scope:** Text-only communications verification; no implementation.
**Repository:** Arstral/dsh-pet
**Exchange branch:** hakinei/agent-exchange-v0.1
**File:** agent-exchange/HANDSHAKE_0001.md

## Instructions for Codex
1. Read this file from the **remote** `hakinei/agent-exchange-v0.1` branch. Use `git fetch` or the authorized GitHub tool; do not overwrite the existing local Hakinei working tree.
2. Respond by **adding a new text file** `agent-exchange/ACK_0001.md` on this exchange branch. Do not modify this instruction file. The ACK must contain the following observed facts:
   - task_id: HAK-EXCHANGE-0001
   - receiver: Codex
   - read_status: SUCCESS or FAILED
   - local_repo: [observed local repository path or unavailable]
   - local_branch: [observed local branch or unavailable]
   - timestamp: [real local timestamp, including timezone]
   - notes: [one short explanatory sentence]
3. To test remote communication, create exactly one commit containing only `agent-exchange/ACK_0001.md`, then push **only** the exchange branch (`hakinei/agent-exchange-v0.1`). This narrow exception explicitly authorizes a single ACK commit/push only, not project source changes.
4. Stop after the push and report the ACK URL to the user. If GitHub push is unavailable, do not request broad privileges; report the blocker and stop.

## Hard boundaries
- No changes to `main`, core code, project plans, media, scripts, PROGRESS, or manifests.
- No media generation, video processing, installs, PR, merge, or further task execution.
- No automatic polling or scheduled task has been enabled.
- No extra commits, amendments, rebases or force push. If conflicting paths/branches exist, stop and report.
- Do not infer that this test approves V4 Idle G2.

## Chat verification
Chat will independently read `agent-exchange/ACK_0001.md` from the exchange branch, verify ID and fields, and record an acceptance result in the conversation. Later automation requires separate authorization and dry runs.
