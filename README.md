# BharatBBQ

This repository accompanies the paper **"BharatBBQ: A Multilingual Bias Benchmark for Question Answering in the Indian Context"**, published in the *Transactions of the Association for Computational Linguistics* (TACL), Vol. 13, and presented at **EMNLP 2025** in Suzhou, China.

Paper: [TACL](https://aclanthology.org/2025.tacl-1.75/) · Preprint: [arXiv](https://arxiv.org/abs/2508.07090) · Dataset: [Huggingface](https://huggingface.co/datasets/aditya20t/BharatBBQ)

## Dataset

The full multilingual dataset is now available — **English and 7 Indic languages**, across **13 social categories** including 3 intersectional groups.

| Config | Language |
|--------|----------|
| `english` | English |
| `hindi` | Hindi |
| `marathi` | Marathi |
| `bengali` | Bengali |
| `tamil` | Tamil |
| `telugu` | Telugu |
| `odia` | Odia |
| `assamese` | Assamese |

All languages are row-parallel and joinable on `id`, so model behaviour can be compared directly across languages on identical items. The benchmark was built from hand-written templates in the Indian sociocultural context and expanded into the seven Indic languages through translation and verification, following the methodology described in the paper.

```python
from datasets import load_dataset

ds = load_dataset("aditya20t/BharatBBQ", "tamil", split="Age")
```

## Repository layout

| Path | Contents |
|------|----------|
| `BharatBBQ_Dataset/Templates/` | Source templates per social category |
| `BharatBBQ_Dataset/Examples/` | Generated English examples |
| `BharatBBQ_Dataset/create_examples.ipynb` | Template → example generation |
| `Metrics/` | Bias and stereotypical-bias scoring |
| `zero-shot.md`, `few-shot-English_instruction.md`, `few-shot_Target_instruction.md` | Evaluation prompts |

## Citation

```bibtex
@article{tomar-etal-2025-bharatbbq,
    title = "{B}harat{BBQ}: A Multilingual Bias Benchmark for Question Answering in the {I}ndian Context",
    author = "Tomar, Aditya  and
      Sahoo, Nihar Ranjan  and
      Bhattacharyya, Pushpak",
    journal = "Transactions of the Association for Computational Linguistics",
    volume = "13",
    year = "2025",
    address = "Cambridge, MA",
    publisher = "MIT Press",
    url = "https://aclanthology.org/2025.tacl-1.75/",
    doi = "10.1162/tacl.a.55",
    pages = "1672--1692"
}
```
