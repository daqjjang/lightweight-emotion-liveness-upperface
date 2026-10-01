# lightweight-emotion-liveness-upperface
Lightweight speech-conditioned upper-face animation via emotion–liveness composition for virtual agents.

# Lightweight Speech-Conditioned Upper-Face Animation for Virtual Agents via Emotion–Liveness Composition

Official repository for the paper:

**Lightweight Speech-Conditioned Upper-Face Animation for Virtual Agents via Emotion–Liveness Composition**

This work presents a lightweight speech-conditioned upper-face animation framework for conversational virtual agents. The framework separates upper-face generation into two components:

- **Emotion generator**: generates nine eyebrow- and eye-region motion channels conditioned on speech, emotion, intensity, and speaker style.
- **Liveness generator**: uses a lightweight CVAE-GAN to model natural upper-face motion variation that is only weakly correlated with speech.

Lip motion is handled separately using an existing real-time lip-synchronization module.

## Method Overview

The proposed framework consists of:

1. An emotion-conditioned upper-face generator
2. A CVAE-GAN-based liveness generator
3. Positive-residual fusion of emotion and liveness motion
4. External real-time lip synchronization

The system directly generates nine upper-face motion channels corresponding to eyebrow and eye-region movements.

## Repository Status

The source code and trained models are currently being prepared for public release.

This repository will be updated with implementation details, model checkpoints, and usage instructions.

## Datasets

The experiments in the paper use the following publicly available datasets:

- MEAD
- BEAT
- RAVDESS

Please refer to the original dataset sources for access and licensing information.

## Citation

BibTeX information will be updated after publication.

## License

License information will be provided when the source code is released.
