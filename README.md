# **🤖 NeRF and 3D Gaussian Splatting Learning Repository**
## **Description**

Welcome! This repository serves as a personal collection of files, articles, papers, and learning resources related to Neural Radiance Fields (NeRF) and 3D Gaussian Splatting (3DGS).


## **What's Inside?**

/articles and links: PDFs and links to influential papers and research articles.

## **Key Concepts**

### Neural Radiance Fields (NeRF)

NeRF is a method that uses a small Multi-Layer Perceptron (MLP) network to implicitly encode a 3D scene. The network learns a mapping from a 5D coordinate (3D location, 2D viewing direction) to a volume density and view-dependent color. This allows for rendering photo-realistic images from new viewpoints.

### 3D Gaussian Splatting (3DGS)

3DGS is a newer, faster technique that represents a 3D scene using a set of explicit 3D Gaussians (ellipsoids). It leverages tile-based rasterization in GPUs for real-time rendering and can be optimized much quicker than NeRF, providing high-quality results.

_______
Contributing

As this is a personal learning repository, contributions are not generally expected, but I welcome suggestions or links to great learning materials via issues.

License

This repository is primarily for educational purposes. All original notes and code snippets are released under the MIT License. Please refer to the licenses of any included external articles or code.
