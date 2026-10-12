<!-- solve-problem:d685d816-e4bb-4880-8e39-014cfac4b372 -->
# ALGO-000010: APSP subcubic barrier

A [Tangle Solve problem](https://solve.tangle.tools/problems/d685d816-e4bb-4880-8e39-014cfac4b372).

Source verification label: flagged. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000010: APSP subcubic barrier
- **Subfield:** fine-grained complexity
- **Open:** Is there a truly subcubic (n^{3-ε}) algorithm for All-Pairs Shortest Paths in weighted graphs?
- **Status:** Open for decades. Best known ~n^3 / 2^{Ω(sqrt log n)} by Williams (2014) building on Chan; equivalent subcubic-hard class (Vassilevska Williams–Williams 2010: APSP, negative triangle, etc. all subcubic-equivalent).
- **Type:** theory
- **Why:** Central to the fine-grained web; many graph problems are subcubically equivalent to it.
- **Key works:** V. Vassilevska Williams, R. Williams, "Subcubic equivalences between path, matrix and triangle problems", FOCS 2010 (arXiv:1011.4901); R. Williams, "Faster all-pairs shortest paths via circuit complexity", STOC 2014 (arXiv:1312.6680)
- **Aliases:** all-pairs shortest paths lower bound
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "flags": [
    "citation-mismatch:1011.4901"
  ],
  "id": "ALGO-000010",
  "label": "flagged",
  "origin": "sourced",
  "source_checked_at": "2026-10-11",
  "source_kind": "manual",
  "source_verified": false,
  "triage": "suspect",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/d685d816-e4bb-4880-8e39-014cfac4b372?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000010.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000010)
