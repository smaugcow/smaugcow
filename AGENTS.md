# Personal GitHub workflow

Use English for README prose, commit messages, pull request titles, and descriptions.
Use `type(scope): short English summary` for commit and pull request titles, without ticket IDs.
Allowed types are `feat`, `fix`, `docs`, `infra`, `perf`, `refactor`, `style`, `test`, `chore`, `build`, and `ci`.
Use a lowercase snake_case scope and an imperative summary of at most 50 characters, without a final period.
Keep commits focused and preserve unrelated work.
Use pull requests for review, with one short summary and the relevant validation results.
Review correctness, security, and scope before submitting a pull request.
Keep README files focused on the project's purpose, behavior, and setup or run commands.
Preserve identifiers, paths, URLs, and literal UI labels when translating documentation.
Never commit secrets, generated credentials, or runtime sessions.
Rewrite shared history only when explicitly requested, and use force-with-lease.
