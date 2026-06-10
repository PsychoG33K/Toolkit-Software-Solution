# Changelog

## CockpitDiag Enterprise v1.0 - Release Candidate Client Controlee

Status: release candidate for controlled customer distribution.

Highlights:

- Proprietary Enterprise licensing model with `license.json` validation.
- Mandatory licensing DLL validation.
- Locked mode when no valid licence is present.
- AutoDiag report generation with manual AI prompt workflow.
- Dark HTML report theme with CockpitDiag branding.
- User Guide images refreshed.
- Runtime logs stored outside the package in local application data.
- Final ZIP packaging checks: no runtime artifacts, no test licence, no private keys, no embedded third-party tools.

Known V1 status:

- Not signed with Authenticode.
- SmartScreen may warn on first launch.
- Trial licences are offline and machine-bound when generated with a machine hash.

## MotherDiag

MotherDiag Community and MotherDiag Technician are managed as separate editions. Public release packaging will be documented separately after final audit and test.

## GitHub Documentation Update - MotherDiag Community

- Added dedicated MotherDiag Community Edition documentation.
- Added Community installation notes.
- Clarified that Community is free proprietary, not open source, and does not require license.json.

