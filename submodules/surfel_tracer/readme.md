# 2D Gaussian Ray Tracer

An OptiX-based differentiable 2D Gaussian Ray Tracer, which is the cuda backend of [IRGS](https://github.com/LogosIntelligenceLab/IRGS).

### Install
```bash
# clone the repo
git clone https://github.com/LogosIntelligenceLab/IRGS.git
cd IRGS/submodules/surfel_tracer

# use cmake to build the project for ptx file (for Optix)
rm -rf ./build && mkdir build && cd build && cmake .. && make && cd ../

# Install the package
pip install .
```

### Example usage
See `surfel_tracer/raytracer.py` for the usage of the 2D Gaussian Ray Tracer. You can also refer to [IRGS](https://github.com/LogosIntelligenceLab/IRGS).

### Acknowledgement

* Credits to the original [3D Gaussian Ray Tracing](https://gaussiantracer.github.io/) paper.

## 📜 Citation
If you find this work useful for your research, please cite our github repo:
```bibtex
@article{gu2024IRGS,
  title={IRGS: Inter-Reflective Gaussian Splatting with 2D Gaussian Ray Tracing},
  author={Gu, Chun and Wei, Xiaofei and Zeng, Zixuan and Yao, Yuxuan and Zhang, Li},
  booktitle={CVPR},
  year={2025},
}
```
