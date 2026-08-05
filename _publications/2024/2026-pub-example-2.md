---
title:          "The PID controller strikes back: Classical controller helps mitigate barren plateaus in noisy variational quantum circuits"
date:           2026-06-14 00:01:00 +0800
selected:       true
pub:            "2026 8th Annual Learning for Dynamics & Control Conference, PMLR"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2026"
# semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776  # use this to retrieve citation count
abstract: >-
  Variational quantum algorithms (VQAs) combine the advantages of classical optimization and quantum computation, making them one of the most promising approaches in the Noisy Intermediate-Scale Quantum (NISQ) era. However, when optimized using gradient descent, VQAs often suffer from the vanishing gradient problem, commonly known as the barren plateau. Various methods have been proposed to mitigate this issue. In this work, we propose a hybrid approach that integrates a classical proportional-integral-derivative (PID) controller with a neural network to update the parameters of variational quantum circuits. We refer to this method as NPID, which aims to mitigate the barren plateau. The proposed algorithm is tested on randomly generated quantum input states and random quantum circuits with parametric noise to evaluate its universality, and additional simulations are conducted under different noise rates to examine its robustness. The effectiveness of the proposed method is evaluated based on its convergence speed toward the target cost value. Simulation results show that NPID achieves a convergence efficiency 2-9 times higher than NEQP and QV, with performance fluctuations averaging only 4.45% across different noise levels. These results highlight the potential of integrating classical control theory into quantum optimization, providing a new perspective for improving the trainability and stability of variational quantum algorithms.
cover:          /assets/images/covers/NPID.pdf
authors:
  - Zhehao Yi
  - Rahul Bhadani
# links:
#  Code: https://github.com/luost26/academic-homepage
#  Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
