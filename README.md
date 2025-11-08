# scoop-monaspace

This Scoop bucket provides manifests for installing the Monaspace font family in multiple variants. Each package downloads the latest release from the upstream GitHub repository at install time, making the fonts available without manual updates while ensuring consistent hash verification via the repository stub.

## Usage

```
scoop bucket add monaspace https://github.com/zaoe/scoop-monaspace
scoop update
scoop install monaspace-static
scoop install monaspace-vf
scoop install monaspace-nerdfonts
```

> The `monaspace-static` and `monaspace-nerdfonts` packages both contain Nerd glyphs—install one or the other to avoid duplicates. The `monaspace-vf` package ships the variable fonts without Nerd glyphs; in editors like VS Code you may want to configure a fallback such as `Symbols Nerd Font Mono`.
