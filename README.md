MI-Zero: Visual Language Pretrained Multiple Instance Zero-Shot Transfer for Histopathology Images
===

## Information

![MI-Zero schematic](repo_assets/wsi_zeroshot.jpg)

<p align = "left">
Figure 1. Schematic of MI-Zero. A gigapixel WSI is converted to a collection of patches (instances), each embedded into an aligned
visual-language latent space. In the set-based representation, the similarity scores between patch embeddings and prompt embeddings
are aggregated via a permutation invariant operator such as topK max-pooling to produce the WSI-level classification prediction. Alternatively, a graph-based representation may be used to incorporate spatial context by first aggregating predictions in local neighborhoods
(Section 3.5 of paper for more details).
</p>

## Installation

This repository includes the inference script for **MI-Zero**. Currently, we only present the script in a notebook for the reviewers' convenience and will refactor into full scripts and release model weights closer to publication. 

Clone the repository with:

```{bash}
git clone https://github.com/anonid12345/MI-Zero
```

