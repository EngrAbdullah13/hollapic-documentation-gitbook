# Supported image formats

Hollapic accepts image uploads through the frontend and stores source/output assets through the backend storage pipeline.

## Confirmed behavior

The backend stores uploaded generation assets with their MIME type and size metadata. The API request body limit is configured to reject oversized payloads with a clear error.

## Recommended formats

- PNG for clean product cutouts or transparent product images.
- JPG or JPEG for photographic product images.
- Web-friendly image files with reasonable resolution and size.

{% hint style="warning" %}
The exact MIME allowlist is enforced by the current upload implementation. If a format is rejected, convert the file to PNG or JPG and try again.
{% endhint %}

## Related guides

- [Upload product images](../product-guide/upload-product-images.md)
- [Recommended source image guidelines](source-image-guidelines.md)
