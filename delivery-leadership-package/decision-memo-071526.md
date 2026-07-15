# Decision Memo — CI Workflow Fix Using AI

**Date:** 7/15/26
**Author:** Tina
**Decision area:** CI Workflow Fix Using AI

## Context
CI Workflow was failing on the required files step. Asked AI why, and it mentioned that the file structure was wrong.

## Recommendation: Direct to the correct file location

Update to look within the delviery-leadership-package to find the required files. No risks.

## Why

CI Workflow will fail to find the required files otherwise.

## What would change my mind

If required files were moved, we would want to revisit where the CI workflow was looking for them.
