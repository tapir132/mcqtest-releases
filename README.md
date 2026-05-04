# MCQTest releases

Public release artifacts for the MCQTest practice-test app. The source code
lives in a private repository.

Each release contains:

- `MCQTest-mac-arm64.zip` — fresh install bundle for Apple Silicon Macs.
- `MCQTest.app.tar.gz` and `MCQTest.app.tar.gz.sig` — used by the in-app
  Tauri auto-updater. End users don't need to download these directly.
- `latest.json` — the updater manifest (polled by the running app).
