---
layout: post
title:  "Faster-LIO: Lightweight Tightly Coupled Lidar-Inertial Odometry Using Parallel Sparse Incremental Voxels"
date:   2021-11-02 18:05:55 +0300
image:  faster-lio.jpg
---
1.	Applied the incremental voxels (iVox) as point cloud spatial data structure (modified from the traditional voxels) to the state-of-the-art positioning algorithm Fast-LIO2 to support incremental insertion and parallel approximated KNN queries.
2.	Proposed the linear iVox and Pseudo Hilbert Curve (PHC) iVox as two alternative underlying structures in the algorithm.
3.	Update the iVox with the least recently used (LRU) cache strategy. Move the newly created voxels and the newly used voxels back, and delete those that have not been used for a fixed period.
4.	The experiments on open-sourced datasets show that the method can significantly increase the running speed with the same accuracy. The paper Faster-LIO: Lightweight Tightly Coupled Lidar-Inertial Odometry Using Parallel Sparse Incremental Voxels was published on RA-L 2022.

