Third‑Party Components and Licences

This project depends on a number of open‑source packages.  The table below lists every direct software component imported in code or used in model training/inference, its upstream repository, and the licence that governs its distribution and use.

Component	Upstream / Home	Licence	Notes on Compatibility
Python (3.x)	https://www.python.org	PSF Licence 2.0	Permissive; compatible with MIT/Apache/BSD.
NumPy	https://github.com/numpy/numpy	BSD 3‑Clause	Permissive.
SciPy	https://github.com/scipy/scipy	BSD 3‑Clause	Permissive.
pandas	https://github.com/pandas-dev/pandas	BSD 3‑Clause	Permissive.
Matplotlib	https://github.com/matplotlib/matplotlib	Matplotlib Licence (BSD‑style)	Permissive.
scikit‑image	https://github.com/scikit-image/scikit-image	BSD 3‑Clause	Permissive.
scikit‑learn	https://github.com/scikit-learn/scikit-learn	BSD 3‑Clause	Permissive.
OpenCV‑Python	https://github.com/opencv/opencv-python	Apache 2.0	Permissive.
AICSImageIO	https://github.com/AllenCellModeling/aicsimageio	BSD 3‑Clause	Permissive.
tifffile	https://github.com/cgohlke/tifffile	BSD 3‑Clause	Permissive.
napari	https://github.com/napari/napari	BSD 3‑Clause	GUI visualisation, permissive.
PyTorch	https://github.com/pytorch/pytorch	BSD 3‑Clause	Permissive; bundled sub‑deps under compatible licences.
TensorFlow	https://github.com/tensorflow/tensorflow	Apache 2.0	Permissive.
Keras	https://github.com/keras-team/keras	Apache 2.0	Permissive.
nnU‑Net	https://github.com/MIC-DKFZ/nnUNet	Apache 2.0	Permissive; training scripts modified in this repo.
Cellpose	https://github.com/MouseLand/cellpose	MIT	Permissive.
CellposeSAM	https://github.com/MouseLand/cellpose	MIT	Same licence as base Cellpose.
Segment Anything (Model) (SAM)	https://github.com/facebookresearch/segment-anything	Apache 2.0	SAM weights used via CellposeSAM.
CUDA Toolkit (runtime only)	https://developer.nvidia.com/cuda-downloads	NVIDIA EULA	Proprietary binary dependency; distribution handled by end‑user installation, not redistributed by this repo.

Licence Compatibility

All permissive licences listed above (MIT, BSD 3‑Clause, Apache 2.0, PSF 2.0) are mutually compatible and allow redistribution of binaries and modified source under the project’s chosen licence (MIT for code, CC‑BY for documentation) provided original copyright notices are retained.

The proprietary NVIDIA CUDA runtime is not redistributed here; users install it separately under NVIDIA’s terms.

Copyright Notice

Copyright © 2025 Noah Wijnheijmer.  This repository’s original source code is released under the MIT Licence (see LICENSE), while all documentation—including this file—is released under CC‑BY 4.0.
