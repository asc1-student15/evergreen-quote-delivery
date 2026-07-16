# Delivery Review — Evergreen Quote

## Slide 1 — Delivery goal & did we hit it?

- Goal (one sentence): Deliver a working quick quote application for new insurance customers
- Hit? x Yes  ☐ Partially  ☐ No
- Despite not having visible Testimonials yet, the main expected functionality of this application has been delivered and is usable for the customer as a result of this week's release.

## Slide 2 — What shipped

- [Link to app.](https://asc1-student15.github.io/evergreen-quote-delivery/)
- [Link to the merged PR.](https://github.com/asc1-student15/evergreen-quote-delivery/pull/7)
- [Link to the green CI run.](https://github.com/asc1-student15/evergreen-quote-delivery/actions/runs/29432648094)

## Slide 3 — Two key decisions

- **Decision 1:** Scope Changes to Testimonials Section  Why it mattered: Commenting out the existing Testimonials code while we wait for approvals from the business provides flexibility in schedule while not losing work already done.
- **Decision 2:** CI Workflow Fix Using AI  Why it mattered: Used AI to fix CI workflow errors, since they were repetitive and it made sense to not spend time making changes manually.
- (See `decision-memo-071426.md` and `decision-memo-071526.md`.)

## Slide 4 — Risks & injects

- Top risk we tracked: Changes to scope or approvals
- Inject #1 (Tue): Legal decided that the Testimonials section should not be included in this release, so we commented out that code and will move forward without it this week. It will be added back in a future release.
Scope was also added to incorporate a new navigation link for 'Compare Plans', but the url was not provided. This link was added into the app but currently does not navigate anywhere, similar to the other links. Once the url is available, a hotfix can be implemented to link it. Go.
- Inject #2 (Wed): Ops alerted us to a Prod bug with the quoting of Renter's coverage, which was related to a failing CI run (missing rating file for Renter's insurance). Development team has been advised to ensure that file is accessible and to prioritize the bug fix, but this new functionality release will not be impacted. Go.

## Slide 5 — What I'd do differently next round

- I would have prefered to have all requirements and links available to implement for the scope creep asks, so maybe there would be some push-back on that ask. Otherwise, I would not do anything differently in the same situations.

## Q&A prep — Likely question responses

- We did not ship the Testimonals section due to the risk of legal repercussions. This will be available in approx. two weeks once approved.
- The links to the navigation bars are currently not functional and will be provided once available.
