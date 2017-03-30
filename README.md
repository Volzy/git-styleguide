# git-styleguide
An opinionated Git styleguide

- [Local commits](#local-commits)
- [Upstream commits](#upstream-commits)
- [Branches](#branches)

## Local commits

TODO: Write about less restrictive local commits before rewriting your history with squash commits

## Upstream commits

```
<Summary>

<Body>

<Footer>
```

#### Summary (mandatory)
Summarize in max 50 characters

> Why? Because this keeps summaries trimmed and overview using `git log --oneline`

Use present tense (e.g. "Add", "Remove", "Fix", "Refactor")

> Why? Because Git per default uses present tense, so you get a cleaner commit history between your own commits and Git merge

```
// Bad
Adding validation

// Bad
Added validation

// Good
Add validation
```

Include scope (e.g. "Payout module" or "User Login")

> Why? Because this increases understanding of what your commit has changes to

#### Body (optional)
- [x] Text wrapped to 72 charaters per line
- [x] No other text length limitations
- [x] Provide useful information such as "the why" or your mindset when you wrote this code

#### Footer (optional)
- [x] Relevant metadata such as Closes #1 or #time 20m (if using JIRA or similar)


## Branches

Categorize branches into three types:

- /feat
- /bugfix
- /release

TODO: Add more branch strategy
