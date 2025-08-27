# ECMRN

## Code of paper "ECMRN: Efficient Cross-Modal Reparameterization Network for RGB-D Tasks via Prompt Tuning"
## 1. Preface
- The complete code will be released after paper acceptance.

## 2. Overview
RGB-D semantic segmentation has shown notable progress by leveraging the complementary characteristics of RGB and depth modalities, substantially enhancing scene understanding. However, existing approaches often depend on dual-encoder architectures, leading to high computational overhead and limited inference efficiency. To overcome these limitations, we propose an Efficient Cross-Modal Reparameterization Network (ECMRN), which integrates prompt tuning with dynamic frequency-domain structural reparameterization for efficient and accurate segmentation. Specifically, we introduce a hybrid RGB-D block that combines a frozen attention branch and a trainable CNN branch, facilitating collaborative modeling of global context and local structures. A Cross-layer Prompt Adapter (CPA) is devised to bridge the modality gap via learnable attention fusion and token interaction, enabling effective semantic alignment across modalities. Moreover, we propose a unified structural reparameterization framework, instantiated in both the stem module and the Dynamic Frequency-domain Reparameterization Module (DFRM), which facilitates expressive multi-branch feature learning during training and is equivalently transformed into a compact single-branch structure at inference for efficient deployment. Additionally, a Multi-scale Feature Optimization Module (MFOM) applies grouped attention at multiple scales to further enhance feature representation. Extensive experiments demonstrate that ECMRN achieves competitive performance in RGB-X tasks with nearly half the parameters of state-of-the-art methods. 

<p align="center">
    <img src="fig2.png"/> <br />
    <em>
    Figure 1: Overview of our proposed ECMRN framework for RGB-D tasks.
    </em>
</p>
