<img width="1509" alt="image" src="https://github.com/user-attachments/assets/b46df8e3-5209-470b-aca1-1a6f6caf48af" />

# Faster Volumetric Cloudscapes with GPU-based Decoupled Ray Marching

## Porting a Monte Carlo volume rendering method into an open-world AAA game engine

### Abstract
Rendering volumetric cloudscapes in real-time is computationally intensive, yet essential for open-world games. The high cost of real-time volumetric cloud rendering primarily stems from the ray marching algorithm, a volume rendering method characterized by a time complexity of $O(n^2)$. An alternative approach in CPU rendering, known as Decoupled Ray Marching [Kulla 2011], optimizes the original algorithm, reducing its complexity to $O(n\log n)$ by decoupling the computation of in-scattering from transmittance and incorporating importance sampling to approximate the final color. The main contribution of this thesis is the adaptation of Kulla's Decoupled Ray Marching algorithm for GPU execution inside Avalanche's Apex Game Engine. This study effectively demonstrates that Kulla’s decoupled ray marching algorithm can be successfully implemented on the GPU, resulting in significant rendering time reductions of up to 30% compared to standard ray marching. However, further research will be necessary to address issues related to noise and optimized GPU memory access.

### Resources
- [Thesis Presentation (PDF)](https://github.com/DavidGiraldoCode/p-MS_Thesis_Faster_Volumetric_Cloudscapes_with_GPU-based_Decoupled_Ray_Marching/blob/main/Ms%20Thesis%20Presentation%20_%20Decoupled%20Ray%20Marching%20in%20Video%20Games.pdf)
- 

<img width="1192" alt="image" src="https://github.com/user-attachments/assets/888c83a7-6220-4362-8ad7-565455429d80" />
