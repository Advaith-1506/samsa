# Contributing

Use a topic branch and keep changes small enough to review. Follow [README.md](README.md) for setup, architecture, validation commands, and current baseline failures. Include the commands you ran and their outcomes in your pull request; do not present known failures as passing checks.

Use synthetic data. Never commit credentials, local environments, dependency folders, or runtime logs. Do not regenerate or delete checked-in datasets, research outputs, or media without explaining provenance and confirming they can be replaced. Check `git diff --check` and review the complete diff before committing.

Documentation changes should match actual paths and handlers. Changes to calculations or scheduling should include independent behavioral checks. Licensing and third-party asset rights require maintainer review.
