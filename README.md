# homebrew-trellis — retired

**The BrainTrellis CLI (`trellis`) was retired on 2026-10-12.** Its login endpoints no longer exist,
so the formula here installs a tool that can't sign in. This tap is archived.

Use BrainTrellis from AI assistants over MCP instead, at `https://braintrellis.com/mcp`. Claude
Code, for example:

```sh
claude mcp add --transport http braintrellis https://braintrellis.com/mcp
```

For scripts, call the HTTP API with a personal token from the Connections page at
<https://braintrellis.com>.

If you installed it: `brew uninstall trellis && brew untap Brightwing-Systems-LLC/trellis`.
