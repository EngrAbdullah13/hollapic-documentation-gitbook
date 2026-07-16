# How Brand DNA affects generation

Brand DNA is applied inside the prompt-planning pipeline.

## Data flow

1. The user completes Brand DNA.
2. The backend builds a compact brand summary.
3. During generation, the user can enable **Use Brand DNA**.
4. The backend verifies eligibility and completion.
5. The generation job stores a snapshot of the brand summary.
6. The prompt planner injects that summary as soft visual guidance.
7. The image generation model receives the final compiled prompt and uploaded images.

## Important behavior

Brand DNA does not send raw profile answers or raw URLs directly to the image generation model. The prompt planner receives the saved summary and creates the final image prompt.

## Related guides

- [Prompt planning pipeline](../developer-guide/prompt-planning-pipeline.md)
- [Brand DNA implementation](../developer-guide/brand-dna-implementation.md)
