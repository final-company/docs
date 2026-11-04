# Final documentation

Mintlify docs for AI coding, the Agent SDK, MCP gateway, Final Device, VMs, CI runners, and
Cloud Apps. Pages are MDX; navigation is in `docs.json`.

## Local development

```bash
npx mint dev
```

## Validate changes

```bash
npx mint validate
npx mint broken-links
```

Keep guides short and task-focused. Use concrete examples and show the expected
result. Verify SDK examples against the published package. Keep private paths,
infrastructure details, and backend implementation out of published content.

## Publication

Push or merge through the repository's normal review workflow to publish changes.
