# CFIR

**CFIR: Fast and Effective Long-Text To Image Retrieval for Large Corpora**  
Zijun Long, Xuri Ge, Richard McCreadie and Joemon M. Jose · SIGIR 2024

CFIR retrieves images from a large collection when the query is a full passage. It first ranks candidates using the entities mentioned in the passage, then re-ranks that shortlist using a summary of the query. The two stages share an image index. The paper evaluates this design on AToMiC, where a long query can describe several plausible images.

[Read the paper on arXiv](https://arxiv.org/abs/2402.15276) · [ACM publication](https://doi.org/10.1145/3626772.3657741)

## Implementation status

This repository currently contains the project overview. Training and retrieval code, pretrained weights and data preparation scripts are not included in this checkout. The paper describes the encoder, the two retrieval stages and the evaluation protocol.

## Citation

```bibtex
@inproceedings{long2024cfir,
  author    = {Long, Zijun and Ge, Xuri and McCreadie, Richard and Jose, Joemon M.},
  title     = {{CFIR}: Fast and Effective Long-Text To Image Retrieval for Large Corpora},
  booktitle = {Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  year      = {2024},
  pages     = {2188--2198},
  doi       = {10.1145/3626772.3657741}
}
```
