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
- [x] Summarize in max 50 characters
- [x] Use present tense (e.g. "Add", "Remove", "Fix", "Refactor")
- [x] Include scope (e.g. "Payout module" or "User Login")

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
