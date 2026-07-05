# scoop-cc-select

Scoop bucket for [cc-select](https://github.com/matiastang/cc-select).

## Install

```powershell
scoop bucket add cc-select https://github.com/matiastang/scoop-cc-select
scoop install cc-select
```

## Upgrade

```powershell
scoop update cc-select
```

## Uninstall

```powershell
scoop uninstall cc-select
scoop bucket rm cc-select
```

## After installation

Enable shell integration by running:

```powershell
cc-select init | Out-File -Append -Encoding utf8 $PROFILE
```

Then reload your profile:

```powershell
. $PROFILE
```

## About cc-select

cc-select is a CLI for shell-level (per-terminal) isolation of AI model providers for Claude Code.

- Main repository: https://github.com/matiastang/cc-select
- Releases: https://github.com/matiastang/cc-select/releases

> This bucket is automatically updated by GoReleaser on every cc-select release.
