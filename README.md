# PineSript v5 Snippets
A collection of version 5 PineScript indicators, strategies and reference materials

**For academic purposes only, devise your own loosing strategies ;0**

## PineScript
A domain-specific programming language used primarily for writing custom technical analysis indicators, strategies, and scripts on the [TradingView](https://www.tradingview.com/) platform

## Running a snippet
PineScript can only be run in the interpreter provided in the SuperCharts section of [TradingView](https://www.tradingview.com/)


## Contribution Guidelines
Always happy to accept contributions, and here's an outline of the development processes to help you along!

### Git: feature branches
The `main` branch is always ready for release, with features developed on their own branches and squash merged only when they are done.

Following the approach outlined by [Trunk based development](https://trunkbaseddevelopment.com/)


### Pull Request
When creating a PR for you feature branch to merge to `main` follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Recommended prefixes:
```text 
build:
chore:
ci:
docs:
fix:
feat:
perf:
refactor:
style:
test:
```


### Code Review
When delivering feedback on a PR follow [Conventional Comments](https://conventionalcomments.org/)

Recommended format:
```text 
<label> [decorations]: <subject>

[discussion]
```

### Definition of Done
Within the constraints that PineScripts brings, a feature is done when...

- Code Completion: All code is written, checked in, and reviewed.
- Code Review: The code has been peer-reviewed and approved.
- Documentation: Relevant documentation is updated, including user manuals, technical documentation, and comments in the code.
- User Acceptance Testing (UAT): The increment has been tested by users and any feedback has been addressed.
- Bug Fixes: All known critical bugs have been fixed and there are no high-severity bugs remaining.
