# Dataset Release Licensing Policy

## Rule

Directly reuse the license from the dataset's direct data sources or the models
used for synthesis. If there are multiple sources, use the one with the most
permissive permissions for derivative and secondary use.

## Interpretation notes

- A synthesis model license may serve as a license source only when its terms
  actually license the data and the generated outputs for downstream use. Read
  the full license text, not only summary tags or commercial-use wording.
- Compare the real obligations each candidate license imposes (for example
  attribution-only, non-commercial, or use-based restrictions), not the tag
  alone.
- The selected license applies to the released dataset as a whole.

## Decision record

Publish the decision by replying on the open release issue with exactly:

```text
Selected license: <license identifier>
Basis: <repository id of the direct input whose license is reused>
```

Then update the dataset card (`README.md`):

1. the YAML `license` field must be set to the selected identifier, and
2. the last line of the card must read exactly
   `The license for this dataset is <license identifier>.`
