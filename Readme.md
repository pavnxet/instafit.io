# instafit.io

An ultra-minimalist, high-contrast client-side utility engine designed to normalize image aspect ratios and frame alignments for modern digital layouts. Completely dependency-free and processed entirely within the local browser runtime framework.

## Architecture & Features

* **Ingestion Core**: Supports dual-mode image provisioning via localized system file streams or standard native Drag and Drop APIs.
* **Canvas Profiler**: Normalizes mismatched horizontal/vertical source matrices into exact targeted standard footprints (`1:1`, `4:5`, `16:9`, `9:16`, `4:3`).
* **Ground Infrastructure**: Toggleable background rendering logic supporting either structural solid white grounds (`#FFFFFF`) or hardware-accelerated dynamic canvas blurring matrices.
* **High-Res Export Pipeline**: Programmatic high-definition canvas down-scaling using a standardized layout matrix coupled with sequential batch delivery streams.
* **Production Naming Strategy**: Eliminates chaotic asset naming conventions by automatically injecting zero-padded hardware execution timestamps (`IMG_YYYYMMDD_HHMMSS_normalized.png`).

## Local Deployment

Since the entire processing framework is self-contained within a unified, stateless presentation layer, it requires zero server runtime compilation:

1. Clone or save the single application distribution bundle (`index.html`).
2. Execute the file directly inside any evergreen web engine:
   ```bash
   open index.html
