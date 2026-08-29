# Fix notes

1. GitHub stats URLs migrated from the unmaintained `github-readme-stats.vercel.app` service to `github-stats-extended.vercel.app`.
2. Activity graph uses the current canonical deployment `github-readme-activity-graph.vercel.app`.
3. Snake workflow now uses `target_branch: output` and `Platane/snk/svg-only@v3`.
4. The snake workflow also runs on push to `main`, so it is generated immediately after committing the workflow.

After pushing these files, open GitHub Actions and run **Generate Contribution Snake** manually once if needed.
