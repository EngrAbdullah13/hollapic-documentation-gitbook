# Upload product images

Product images are the source of truth for the generated output.

## Before you begin

- Confirm the selected workflow requirements.
- Prepare product and reference images when the workflow needs them.

## Steps

1. Open Studio.
2. Select a workflow.
3. Use the required upload node for the product image.
4. Add required reference images for workflows such as Product Swap, Style Copy, or Background Replace.
5. Confirm previews appear in the upload nodes.

## Expected result

The upload node reserves the image space and shows the selected image. Generated jobs store source assets and output assets separately.

## Important behavior

The prompt planner analyzes images in ordered workflow-specific slots. For most workflows, the first image is the product source. For collection workflows, multiple product images can be used.

## Related guides

- [Reference-image behavior](../generation-workflows/reference-image-behavior.md)
- [Supported image formats](../getting-started/supported-image-formats.md)
