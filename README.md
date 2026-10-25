# Clean advisory pilot installation

Disposable consumer repository for Workflow Privilege Check 0.2.0.
The installed workflow is copied directly from the public Action example, pinned
to a reviewed full commit. This repository contains no scanner implementation,
internal test runner, summary-capture hook, policy defaults, or secrets.

The two manual-only workflows are synthetic input fixtures. PRs exercise neutral
edits, configured grants, incomplete defaults and unsupported YAML aliases.
Advisory warnings are not clean analyses or approval to merge. The pilot workflow
is not a required merge check. Remove it by deleting its workflow file.

Action source: https://github.com/adi271213/workflow-privilege-check

Neutral initial-version fixture edit.
