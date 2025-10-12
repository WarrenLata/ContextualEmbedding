# ContextualEmbedding

A small playground for **text embeddings** (TF-IDF, SBERT) and **RAG**, with rigorous evaluation:
- Paired permutation tests
- Power analysis & calibration
- Multiple testing (FDR) and effect sizes

## Contents
- `abtest.ipynb` — TF-IDF vs SBERT classification + permutation test, power analysis
- `ContextualEmbedding.ipynb` — minimal RAG pipeline (indexing, retrieval, response)

## Reproduce
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r req.txt
# optional: set CUDA_VISIBLE_DEVICES=0
jupyter lab
