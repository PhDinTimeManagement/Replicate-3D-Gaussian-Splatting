# Note for replicating 3D Gaussian Splatting Repository

## Credit to
- Original Repository https://github.com/graphdeco-inria/gaussian-splatting
- Convolve AI Tutorial https://www.youtube.com/watch?v=YksCJ6v96eQ

## Inportant Note to submodules folder
- There are three modules
  - diff-gaussian-rasterization
    - Based on Cuda code (accelerated rust rising)
  - fussed-ssim
  - simple-knn
    - Used to determine the nearest Gaussian point

## Setup
- Clone the repository along with the submodules
  - Method 1 (GUI): Using GitHub Desktop or Pycharm
  - Method 2 (CLI: `git clone https://github.com/graphdeco-inria/gaussian-splatting.git --recursive`
- 