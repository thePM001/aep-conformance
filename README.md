# AEP Conformance Test Suite

Test battery that determines who gets to claim AEP-compliance.

## Status

Pre-v1.0 scaffolding. Tests under active authoring.

## License

Fair Core License 1.0. Converts to Apache 2.0 after 24 months per version. See `LICENSE` for terms.

## What This Gates

The reserved names "AEP", "AEP-compliant", "dynAEP" are subject to a name policy published at `github.com/thePM001/AEP-agent-element-protocol/blob/main/NAME-POLICY.md`. Implementations may use these names only after passing this test suite and submitting a conformance report to the public registry.

## Running the Suite

```bash
./runner/run.sh /path/to/your/bridge
```

(Runner scaffolding lands in a forthcoming commit.)

## Submitting a Conformance Report

Open a PR against `registry/reports/` with a signed JSON report. Format defined in `REGISTRY.md` (forthcoming).
