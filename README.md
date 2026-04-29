# claude-skills

Marketplace for Jbrawner's Claude Code skill bundles. One file does the work: [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json).

## Install

Add the marketplace once:

```
/plugin marketplace add https://github.com/Jbrawner/claude-skills
```

Then install any bundle below by name:

```
/plugin install <name>@claude-skills
```

## Bundles

| Name | What it does | Source |
|---|---|---|
| `tld` | Test-Led Development skills — milestone-driven workflow over Linear, hard stops between phases, drift detection against ticket spec | [Jbrawner/tld-skills](https://github.com/Jbrawner/tld-skills) |

After install, every command from a bundle is namespaced under the bundle name (e.g., `tld` becomes `/tld:help`, `/tld:setup`, `/tld:build`, …).

## License

MIT.
