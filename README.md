# Reusable Workflows

This repository contains reusable organization workflows for GitHub Actions. 
These workflows are used to automate daily tasks, such as assigning PR labels, 
code quality reviews, or automated releases.

## NodeJS

All NodeJS-specific workflows use the prefix `nodejs-`. Available workflows:

* `nodejs-lib-check` — runs configurable code quality checks for a Node.js 
project, including build, tests, static analysis, and optional type checking;

* `nodejs-lib-release-draft` — generates a draft release, calculating the next
semantic version from PR labels, and creating release notes from the target 
branch or commit;

* `nodejs-lib-release` — packages a tagged release, publishes it to npm, 
and commits the released version.
