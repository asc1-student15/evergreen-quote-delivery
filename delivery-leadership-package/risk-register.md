# Risk Register

| # | Risk | Owner | Likelihood (L/M/H) | Impact (L/M/H) | Mitigation | Trigger to escalate |
|---|---|---|---|---|---|---|
| R1 | _e.g., theme.css conflicts with Bootstrap defaults and breaks layout_ | _name_ | M | M | _e.g., test on 375px / 768px / 1280px after every paste_ | _e.g., layout still broken at 16:00 Day 2_ |
| R2 | Zip validation is weak - malformed entries can occur unchecked | Tina | M | H | Add validations around entry values | test failures |
| R3 | Pricing logic fails on unknown coverage types | Tina | L | H | Add tests to fail fast | test failures |
| R4 | Use of 3rd party bootstrap assets adds dependency | Dev-ABC | L | M | set up dependabot monitoring | loss of formatting for page is noticed |
| R5 | "About" navigation link breaks | Tina | M | M | Set footer value to a matching id | link is not accessible |
| R6 | Changes to scope or approvals | Tina | M | M | Conduct decision assessment and update priorities | missing requirements |

## How I'll use this register
This risk register should be reviewed and updated during standup with the project team daily while the initiative is underway, so mitigate any issues efficiently.
