# Week 4

**Dates:** 06-29 to 07-03

## Goals
- Finish writing introduction by clearly defining research problem and adding context to problem at hand (significance and relation to existing work). 
- Develop preliminary methodology by using project proposal as a starting point for the system's code flow. Split methodology into encoder-decoder architecture, style transfer neural net, and semantic info preservation mechanism.
- Narrow down important repositories for similar software for any stage of the style transfer pipeline. Copy code locally and experiment with possibilities of integration into own system.
- Identify relevant open-source repositories to evaluate whether their methods can be adapted/integrated into this system.

## Approach and Implementation
- Expanded introduction to include project's motivation, current limitations, and application context.
- Refined the research objective and described how the proposed work may address an identified gap in style-transfer + projection based systems.
- Translated project proposal into a preliminary workflow by outliing inputs, outputs, model componenets, and intermediaries.
- Identify main respositories implementing relevant architectures and reviewed documentation, pretrained models, dependencies, and datasets.
- Cloned selected repositories into local development environment and conducted prelimiary experiments to assess code functionality.

## Results
- Completed a revised introduction that establishes the research motivation, technical context, related fields, and intended contribution.
- Developed a preliminary system architecture and code flow for the proposed methodology.
- Defined the expected interactions of the three primary model components (encoder/decoder, style transfer, and semantic preservation).
- Identified a focused set of repositories that may support the implementation for individual pipeline stages:
    - Encoder/Decoder Injection: https://github.com/NVlabs/MUNIT, https://github.com/naoto0804/pytorch-AdaIN
    - Style Transfer: https://github.com/jgkwak95/AU-GAN
    - Semantic Preservation: https://github.com/VITA-Group/ShapeMatchingGAN
- Gained initial understanding of modifications required to integrate similar structures to existing implementations.

## Notes
- The next step is to select a baseline implementation and establish a reproducible experiment.
- For this step, each component should be tested independently before integration into the complete pipeline.
