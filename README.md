# xlsft Scoop bucket

Scoop manifests for xlsft tools on Windows.

```powershell
scoop bucket add xlsft https://github.com/xlsft/scoop-bucket
scoop install <tool>
```

| Tool | |
|---|---|
| [ymcp](https://github.com/xlsft/ymcp) | YouTrack MCP server: `scoop install ymcp` |

Manifests are written by each tool's release workflow ([GoReleaser](https://goreleaser.com)); don't edit them by
hand. To add a tool, point its `scoops` at this repository.
