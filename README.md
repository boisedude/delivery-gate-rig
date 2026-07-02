# delivery-gate-rig

Deterministic GitHub rig for the AGLedger software-delivery recipe
(agledger-testbed `recipes/software-delivery/`). Public scratch repo; contains no
application code. The `gate` workflow's conclusion is a pure function of the
committed `quality.status` file, so both CI outcomes are reproducible on demand.
The `author-pr` workflow opens pull requests as `github-actions[bot]`, giving the
authoring agent an identity distinct from the human reviewer.
