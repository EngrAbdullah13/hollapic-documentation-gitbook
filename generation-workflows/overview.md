# Generation workflows overview

Generation workflows tell Hollapic how to interpret the uploaded product image, reference images, optional answers, Brand DNA, and custom instructions.

## Confirmed workflows

| Workflow | Main purpose |
| --- | --- |
| General Image | Create a complete commercial product or lifestyle image. |
| Background Replace | Preserve the product composition and replace the background or environment. |
| Product Swap | Place the uploaded product into a reference scene. |
| Style Copy | Follow a reference look while keeping the uploaded product identity. |
| Label Generation | Create packaging or label concepts. |
| Image Banner | Create ecommerce marketing or ad banners. |
| Packaging Mockup | Create realistic packaging presentations. |
| Collection Image | Arrange multiple products together. |
| Product Infographic | Create feature callout images. |

## Important behavior

The prompt planner creates one optimized prompt before the image model runs. Brand DNA and workflow guidance are handled by the prompt planner, not by sending raw brand setup data directly to the image generation model.

## Related guides

- [Choose the correct workflow](choosing-workflow.md)
- [Generation type reference](../reference/generation-type-reference.md)
