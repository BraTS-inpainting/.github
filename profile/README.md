# 🎨 BraTS Inpainting Challenge

Welcome to the official GitHub organization of the **BraTS Inpainting Challenge**: *Local Synthesis of Healthy Brain Tissue via Inpainting*.

<img width="3200" height="1800" alt="Overview of the BraTS inpainting challenge: healthy brain tissue is synthesized in masked regions of T1-weighted brain MRI scans" src="https://github.com/user-attachments/assets/68155f3e-fbf1-467f-abc7-c99210863120" />

## 🧠 Why inpainting?

Many established tools for brain MRI analysis, such as registration, parcellation, or brain extraction, were developed for healthy brains and can fail when a tumor or lesion is present. Realistically, filling in pathological regions with healthy-looking tissue makes these tools usable again for patient data and opens the door to applications such as counterfactual analysis and controlled stress-testing of downstream models.

## 🎯 The task

This challenge benchmarks generative methods for **inpainting healthy brain tissue** in **T1-weighted MRI scans**. Participants receive partially masked T1 scans from real patient data and reconstruct the missing regions as realistically as possible, without access to the original ground truth.

The goal is **anatomically plausible 3D completion** of irregularly shaped regions in brain MRI, with a focus on **perceptual quality** and **structural realism**.

## 📅 Editions

The challenge launched at **MICCAI 2023** and has run every year since as part of the BraTS family of challenges.

| Edition | Repository |
|---|---|
| 🆕 2026 | [2026_challenge](https://github.com/BraTS-inpainting/2026_challenge) |
| 2025 | [2025_challenge](https://github.com/BraTS-inpainting/2025_challenge) |
| 2024 | [2024_challenge](https://github.com/BraTS-inpainting/2024_challenge) |
| 2023 | [2023_challenge](https://github.com/BraTS-inpainting/2023_challenge) |

Each repository contains everything participants need for that edition, such as baseline models and scripts for generating inpainting masks.

## 🚀 Getting started

1. Head to the repository of the **[current edition](https://github.com/BraTS-inpainting/2026_challenge)** for data access, baselines, and submission instructions.
2. Evaluate your results locally with our official **[metrics package](https://github.com/BraTS-inpainting/inpainting)**, which computes the same metrics used for the challenge leaderboard.
3. Want to use top-performing models from previous editions? They are packaged in the **[BraTS Orchestrator](https://github.com/BrainLesion/BraTS)**, part of the [BrainLesion Suite](https://github.com/BrainLesion).

## 📄 Challenge paper

The dataset, task design, evaluation protocol, and results are described in our official publication. If you use the challenge data or tools, please cite:

> Kofler, F., Meissen, F., Steinbauer, F., Graf, R., Ehrlich, S. K., Reinke, A., Oswald, E., Waldmannstetter, D., Hoelzl, F., Horvath, I., et al. *The Brain Tumor Segmentation (BraTS) Challenge: Local Synthesis of Healthy Brain Tissue via Inpainting.* [arXiv:2305.08992](https://arxiv.org/abs/2305.08992)

## 🤝 Organizers

The BraTS inpainting challenge is a community effort, organized by an international team of researchers, clinicians, and data contributors from many institutions, whose dedication makes each edition possible. The full list of organizers and contributors can be found in the [challenge paper](https://arxiv.org/abs/2305.08992).

The challenge is coordinated by **[koflerlab](https://github.com/koflerlab)** at the Hertie Institute for AI in Brain Health, University of Tübingen.

## 📢 Stay in touch

- Follow us on [Twitter/X](https://x.com/BraTS_inpaint) for announcements and results
- Questions about the challenge? Open an issue in the repository of the current edition

---

🎨 Happy inpainting!
