# Repository Instructions

## Project Goal

This repository is a curated, Persian-language directory of AI, Vibecoding, development, design, automation, infrastructure, and productivity tools for Persian-speaking users. It must stay simple, readable, and easy to maintain over time.

The directory reflects tools the maintainer has personally used or reviewed and found practical; it deliberately does not aim to be exhaustive, and the absence of a tool is not a judgement against it.

## Primary Files

- `README.md`: public tool directory and contribution guide.
- `AGENTS.md`: operational instructions for agents maintaining the directory.

## Language Rules

- README headings, descriptions, contribution instructions, and public-facing text must be Persian.
- Preserve official product/project names in their original language.
- Keep URLs, code, commands, and technical identifiers unchanged.
- Agent-facing instructions (this file) remain English.

## Entry Format

Each tool is one row in a Markdown table with this exact format:

| ابزار | توضیح | لینک |
|---|---|---|
| [Tool Name](URL) | Persian concise factual description. | [باز کردن](URL) |

Additional rules:

- One tool per row; use the official tool/project name when available.
- Descriptions: one sentence, ideally 8–25 Persian words; never place raw URLs in the description column.
- Use the same URL for the tool-name link and the `باز کردن` link unless there is a compelling reason not to.
- Sort entries alphabetically by tool name when names are Latin; sort naturally in Persian for Persian names.
- Place a tool in exactly one primary category; cross-link only if it materially improves discovery.
- If an entry is a collection/gallery rather than a software product, describe it as a resource, gallery, or inspiration source.

## Workflow for New Submissions

When the user provides one or more tools, links, rough notes, markdown links, GitHub URLs, or unstructured lists:

1. Parse each candidate entry.
2. Identify the name, canonical URL, likely category, and concise Persian description.
3. Inspect the linked resource when browsing/repository inspection is available.
4. Never fabricate details if the resource cannot be inspected.
5. Check all existing README entries for duplicates by:
   - identical URL
   - normalized URL
   - identical project/tool name
   - obvious aliases or official repository/site pairs
6. For duplicates:
   - Do not create a second entry.
   - Improve the existing entry only if the new input provides clearer verified information.
7. Place the entry in exactly one primary category.
8. Add a new category only if no existing category is appropriate and at least two entries are likely to belong there over time. Otherwise use `سایر ابزارها`.
9. Keep entries sorted according to README rules.
10. Update the table of contents if top-level categories change.
11. Preserve valid existing content and make minimal, focused edits.
12. Report:
    - added entries
    - updated entries
    - skipped duplicates
    - unclear entries requiring review
    - files changed

## Categorization Guidance

- Design inspiration, UI galleries, visual references → `طراحی UI/UX و الهام بصری`
- Navbar, hero, footer, CTA, page-section libraries/galleries → `کامپوننت‌ها و بخش‌های وب‌سایت`
- Motion, interactions, animation references/tools → `انیمیشن، Motion و Interaction`
- AI-assisted coding environments and autonomous code agents → `AI Coding Agents و Vibecoding`
- MCP servers, agent skills, agent frameworks → `MCP، Agent Skills و Agent Frameworks`
- Deployment, Docker, hosting, VPS, observability, security → `DevOps، سرور و زیرساخت`
- WordPress, WooCommerce, plugins, themes, CMS workflows → `WordPress، WooCommerce و CMS`
- Automation platforms, bots, integrations, workflow tools → `اتوماسیون و Workflow`
- Tools that do not fit reliably → `سایر ابزارها`

Other README categories (use when entries exist for them): `ابزارهای AI و مدل‌ها`, `توسعه وب و Frontend`, `دیتابیس، Backend و API`, `بهره‌وری و مدیریت دانش`, `منابع آموزشی و داکیومنتیشن`.

## Description Guidelines

- Write Persian descriptions that are factual, compact, and useful.
- State what the tool does, not marketing claims.
- Avoid unsupported adjectives such as "best", "powerful", "professional", or "popular".
- Do not claim a tool is free, open source, privacy-preserving, secure, or self-hosted unless verified.
- If uncertain, write: `منبعی برای ...؛ نیازمند بررسی جزئیات.`

## Quality Rules

- Prefer official websites, official GitHub repositories, and primary documentation.
- Keep only relevant, functioning, non-spam resources.
- Do not add affiliate, referral, tracking, shortened, or suspicious links unless the user explicitly requests it.
- Never modify repository configuration, licenses, dependencies, workflows, or code unless explicitly requested.
- Do not make external side effects such as commits, pushes, issues, pull requests, or releases without explicit user approval.

## Final Response Format

After every maintenance task, respond in Persian with:
1. A short summary.
2. Added tools and their categories.
3. Duplicates skipped or entries updated.
4. Any entries that need clarification.
5. Files changed.
