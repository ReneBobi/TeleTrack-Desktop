# CLAUDE.md

<!-- crew:start (maintained by the Agent Office crew council; edits inside are read by the council) -->
## Crew lessons

## Crew notes (teletrack-desktop)

- **What this repo is:** the GitHub Releases auto-update feed and installer host for the TeleTrack desktop client, a thin viewer. It contains only `README.md` and no application source. The client is built elsewhere.
- **Releases are production.** Installed clients download whatever is published here. Never create, publish, edit, delete or re-tag releases or assets without explicit instruction from the owner.
- **Confirm the update format before touching releases.** The asset names, update-metadata files (e.g. `latest.yml`) and versioning scheme the updater expects are not documented here. Check them against the client source before acting, and ask if they are unknown.
- **No toolchain exists.** There is no build, test, lint or CI. Do not invent commands, manifests or pipelines. If one is added, document it in the README and here.
- **README accuracy:** describe only what is actually in the repo or release feed. Mark unknowns explicitly as unknown.
- **Bilingual:** the owner works Slovenian-first, with English alongside. Keep user-facing docs consistent with that when extending them.
- **Secrets:** never commit signing keys, tokens or credentials alongside release artifacts. Release builds must be scrubbed for leaks.
<!-- crew:end -->
