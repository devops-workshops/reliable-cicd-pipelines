# What you will get out of this

After this workshop you should be able to write a basic CI pipeline in two
tools.

## Ideas

- Break a literary work into chapters
- Write tests to test each chapter with characteristics (characters, length,
  etc, time to read estimates, md-lint, spelling)

## Requirements

- Github account
- Have `git` installed locally (git bash command-line)
- Basic knowledge of Bash and command line terminals
- Basic knowledge of git (git branch, git commit, git push, git merge, git pull)
- Docker installed locally

# Parts

This module is broken up into a few parts which will guide us through the basics
and layer on some more advanced topics once each part is completed.

## Part 1

- Describing why pipelines: Linting, tests (unit vs integration vs system),
  security scans, business logic or team standards, semver
- Basic concepts: terminal exit codes, good Bash practices (`set -euo
  pipefail`), debugging locally
- Implement, then implement wrong to make sure it breaks in a known way
- Setup a simple linter and tests locally
- Transferring that local context to a pipeline service
- Rewrite that pipeline in a different tool

## Part 2

- Different pipelines for different branches or PRs
- Secrets in pipelines
- Caching (artifacts and other libraries)
- Publishing artifacts

## Part 3

- What is CD (delivery vs deploying) Publishing vs actually running the code in
  production
- What if this wasn't application code? Infra as Code
