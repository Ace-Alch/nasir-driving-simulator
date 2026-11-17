# Nasir Driving Simulator: validation

## Current evidence

This documentation update inspected available text and file inventories. It did not execute the project, simulate a model or test hardware. Existing recorded results must be cited with their original conditions.

## Proposed checks

These are test plans. No row below is marked as passed.

| Check | Action | Evidence to retain | Status |
| :-- | :-- | :-- | :-- |
| V01: Real driving records | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V02: Simulator records | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V03: Feature analysis | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |
| V04: KNN comparison | Inspect the relevant artifact and run one normal case plus one boundary case. | Source revision, inputs, expected result, observed result and log or image. | Not run |

## Project-specific checks

- Verify or recover: Dataset fields and sampling rates.
- Verify or recover: Train and test split.
- Verify or recover: K and distance metric.
- Verify or recover: Confusion matrix and participant counts.

## Reporting rule

Report units, sample size, configuration, error bounds and failures. Separate a simulation result from a hardware result. Separate an emulator check from a physical-device check. A screenshot alone does not establish numerical accuracy.
