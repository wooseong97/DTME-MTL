# Resolving Token-Space Gradient Conflicts: Token Space Manipulation for Transformer-Based Multi-Task Learning [ICCV 2026]

**Official PyTorch implementation of [*Resolving Token-Space Gradient Conflicts: Token Space Manipulation for Transformer-Based Multi-Task Learning*] [ICCV 2026].**

Wooseong Jeong & Kuk-Jin Yoon, Korea Advanced Institute of Science and Technology (KAIST)

Multi-Task Learning (MTL) enables multiple tasks to be learned within a shared network, but differences in objectives across tasks can cause negative transfer, where the learning of one task degrades another task's performance. While pre-trained transformers significantly improve MTL performance, their fixed network capacity and rigid structure limit adaptability. Previous dynamic network architectures attempt to address this but are inefficient as they directly convert shared parameters into task-specific ones. We propose Dynamic Token Modulation and Expansion (DTME-MTL), a framework applicable to any transformer-based MTL architecture. DTME-MTL enhances adaptability and reduces overfitting by identifying gradient conflicts in token space and applying adaptive solutions based on conflict type. Unlike prior methods that mitigate negative transfer by duplicating network parameters, DTME-MTL operates entirely in token space, enabling efficient adaptation without excessive parameter growth. Extensive experiments demonstrate that DTME-MTL consistently improves multi-task performance with minimal computational overhead, offering a scalable and effective solution for enhancing transformer-based MTL models.

## We are preparing the code for public release. It will be available here soon.

## Contact
Wooseong Jeong: stk14570@kaist.ac.kr
