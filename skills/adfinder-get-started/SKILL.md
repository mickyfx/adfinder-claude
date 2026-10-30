---
name: adfinder-get-started
description: Connect AdFinder to Claude or Claude Code and explain available searches when the user asks to start, sign in or reconnect.
---

Read [the tool-use guide](../../TOOL-CONTRACT.md) before using AdFinder tools.

Use the host’s connection UI and AdFinder OAuth page; never request credentials in chat. In Claude, the bundled connector is connected in the plugin’s Connectors tab; Claude Code uses its MCP authentication flow. A working connection in one host does not establish another’s state.

After connection or an explicit start request, call the exposed `adfinder_balance` once, then `adfinder_discover` with `{"category":"ads_and_sponsored_content"}` for general or competitor-ad onboarding; use a relevant category for another explicit intent. Limit generic onboarding to these two free planning calls. Do not paginate, describe every option, estimate every option or run paid research for the introduction.

Present 5–7 short options and 2–3 example prompts in the user’s language: competitor ads by brand/keyword/ad link; supported market/status/date filters; compare messages and creatives; browse available media; public X/Twitter and Reddit posts (organic); profiles/transcripts; shared balance. Show only the returned balance, with any review bonus separate. Explain that relevant schemas and a bounded cost quote follow the user’s chosen target; a partial catalog or hidden individual tool does not prove a capability unavailable. Invite a brand, keyword or ad link and desired scope. Do not promise automatic onboarding unless the host invokes it.

Examples: “Find Nike ads in the United States”; “Compare Nike and Adidas ad hooks within 5 credits”; “Research a competitor’s public Reddit posts.” No research is authorized merely by loading this Skill.
