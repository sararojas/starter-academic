---
title: "AdvPC: Transferable Adversarial Perturbations on 3D Point Clouds"
publication_types:
  - "1"
authors:
  - Abdullah Hamdi
  - Sara Rojas
  - Ali Thabet
  - and Bernard Ghanem
publication: " European conference on computer vision"
publication_short: In ECCV 2020
abstract: "Deep neural networks are vulnerable to adversarial attacks, in which
  imperceptible perturbations to their input lead to erroneous network
  predictions. This phenomenon has been extensively studied in the image domain,
  and has only recently been extended to 3D point clouds. In this work, we
  present novel data-driven adversarial attacks against 3D point cloud networks.
  We aim to address the following problems in current 3D point cloud adversarial
  attacks: they do not transfer well between different networks, and they are
  easy to defend against via simple statistical methods. To this extent, we
  develop a new point cloud attack (dubbed AdvPC) that exploits the input data
  distribution by adding an adversarial loss, after Auto-Encoder reconstruction,
  to the objective it optimizes. AdvPC leads to perturbations that are resilient
  against current defenses, while remaining highly transferable compared to
  state-of-theart attacks. We test AdvPC using four popular point cloud
  networks: PointNet, PointNet++ (MSG and SSG), and DGCNN. Our proposed attack
  increases the attack success rate by up to 40% for those transferred to unseen
  networks (transferability), while maintaining a high success rate on the
  attacked network. AdvPC also increases the ability to break defenses by up to
  38% as compared to other baselines on the ModelNet40 dataset. The code is
  available at https://github.com/ajhamdi/AdvPC ."
draft: false
featured: false
image:
  filename: https://arxiv.org/pdf/1912.00461.pdf
  focal_point: Smart
  preview_only: false
date: 2020-06-21T06:59:56.721Z
---
