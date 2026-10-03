# Journal

## 2026-10-03 13:05 - Scaffolded solution, API, and test project
- Did: Cloned the GitHub repo (it already had README + LICENSE), added the .NET gitignore, created `FreelancerTracker.slnx` with `api/` (webapi, controllers) and `api.tests/` (xUnit) referencing `api`.
- Decided: Cloned instead of `git init` and adding a remote, so the existing GitHub commit stays in the history and nothing has to be merged.
- Why: Week 1 of the 6-week plan. `api.tests` was first created from the `webapi` template by mistake. `dotnet test` built it, found no tests, and printed nothing. Recreated it from the `xunit` template. What marks a project as a test project is `Microsoft.NET.Test.Sdk` plus the xUnit packages.
