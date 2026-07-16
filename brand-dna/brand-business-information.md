# Brand and business information

The brand and business fields establish the core identity used in the Brand DNA summary.

## Required fields

| Field | Required | Notes |
| --- | --- | --- |
| Brand or business name | Yes | Stored as the brand name in the summary. |
| What do you sell? | Yes | Stored as the offer/product category context. |

## Important behavior

These fields are sanitized and length-limited on the server. They are used to create the saved summary but are not sent as raw URLs or uncontrolled instructions to the image model.

## Related guides

- [How Brand DNA affects generation](how-brand-dna-affects-generation.md)
