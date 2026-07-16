# Week 5

**Dates:** 07-06 to 07-10

## Goals
- Go through MUNIT architecture to emulate encoder-decoder system. Understand training and style injection mechanisms through repository.
- Evaluate/isolate AU-GAN and ShapeMatchingGAN as potential independent modules for style transfer and semantic preservation.
- Begin developing a standalone encoder–decoder implementation that does not depend on an existing style-transfer/semantic preservation framework.

## Approach and Implementation
- Reviewed MUNIT paper and traced the main architectural components within the codebase. Examined how MUNIT represents content and style as seperate latent variables.
- Examined how MUNIT injects style informaiton into decoding process.
- Studied training pipeline (image reconstruction) and associated loss function. Compared MUNIT structure with requirements of the proposed projection-content transfer system.
- Reviewed AUGAN and ShapeMatchingGAN repositories to identify inputs, outputs, dependencies, and possible integration points.
- Began implementing standalone ecoder-decoder architecture to serve as a baseline for system and future integration experiments.

## Results
- Developed a clearer understanding of MUNIT’s content style disentanglement and style-injection mechanism.
- Identified components that may be adapted conceptually for the proposed system.
- Identified potential ompatibility requirements for integrating AU-GAN and ShapeMatchingGAN into the broader pipeline.

## Notes
- The next step is to verify the standalone encoder–decoder model using a small dataset and confirm that its inputs behave as expected.
- Future experiments should evaluate each module independently before combining them into a unified pipeline.
