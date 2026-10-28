# Spline Studio releases

Downloads for **Spline Studio**. Source is private; this repo holds release files and the workflow
that builds them (`.github/workflows/release.yml`), which runs here because Actions minutes are
free on public repositories.

Each [release](https://github.com/chenzizhen237-crypto/spline-releases/releases/latest) has:

- `spline-studio-<tag>-server.tar.gz`: the server and built editor. Unpack, then `pnpm install && pnpm start`.
- The macOS desktop app (Electron, Apple Silicon) as `.dmg` and `.zip`. It isn't signed: the first
  time, right-click Spline Studio in Applications and choose Open.
