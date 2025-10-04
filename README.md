# SegFusion (placeholder during peer review)

This repository documents the release plan and reproducibility checklist for SegFusion.  
No source code is included during review.

## Release plan
- Camera-ready: inference code, evaluation scripts, configuration files.
- Within 30 days after online publication: training code and checkpoints.
- A git tag will match the camera-ready version cited in the paper.

## Reproducibility
- Environment: `environment.yml` (conda) and `requirements.txt` will be provided with CUDA/driver and OS versions.
- Determinism: seeds and flags will be listed for reproducible runs.
- Configs: each experiment is specified by a single YAML file.
- Commands: one-line scripts to reproduce reported tables and figures.
- Expected outputs: paths and metrics will be documented.

## Data
This project does not redistribute datasets. Preparation scripts and instructions will be provided for:
- LLVIP
- M3FD
- Drone
- MSRS
- RoadScene
Users must follow the original dataset licenses.

## Third-party components
SegFusion relies on external projects for prompts, localization, and mask generation:
- LLaVA
- ZipCLIP
- SAM

Their licenses and usage terms remain with the original authors. This repository will include wrappers and configuration only.

## License and intended use
During review, this repository serves research reproducibility only.  
The final license for our code will be posted at release.

## Citation
A `CITATION.cff` and a BibTeX entry will be added upon acceptance.

## Contact
Please open an issue for questions.  
Email: lcwdzkd@163.com
