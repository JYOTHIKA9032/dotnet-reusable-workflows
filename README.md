# REPO1 - Reusable Workflows (.NET 8 + Docker)

Reusable workflows (each in its own YAML):
- `.github/workflows/dotnet-build.yml`
- `.github/workflows/dotnet-test.yml`
- `.github/workflows/dotnet-publish.yml`
- `.github/workflows/docker-build.yml`
- `.github/workflows/docker-push.yml`

All are triggered via `workflow_call` and are meant to be called from an application repo.
