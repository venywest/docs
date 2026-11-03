> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Prefer **envelope** for a signing request in the product UI (`1 envelope = 1 completed signing process`)
- **Self sign** / **Autofirma** is unlimited on public plans and does not use the monthly envelope quota
- Use **workspace** not "project"; **member** for the `member` role
- Plan names: **Starter**, **Pro**, **Business**, **Scale** (internal Pro id may still be `plan_team`)

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document the customer workspace only (owners, admins, members, signers, public verify).
- Document Settings → API and `/api/v1` routes the customer key can call.
- Do not document Super Admin, `/admin`, platform secrets, or internal operators.
