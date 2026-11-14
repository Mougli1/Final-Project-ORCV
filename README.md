# What is time? Motion understanding from frozen visual encoders

Final project for *Object Recognition and Computer Vision* (MVA, 2026), Topic D.

This project compares frozen DINOv3 (image) and V-JEPA 2.1 (video) features on Something-Something V2: first with linear probing, then with small temporal heads on top of the per-frame features.

For now `linear_probing.ipynb` only runs the linear probing on synthetic features (same shape as the real ones: 16 frames, 768 dims, 174 classes), so the numbers in it don't mean anything yet.

Still to do: feature extraction on SSv2, temporal heads, per-class analysis.

## Usage

```bash
pip install -r requirements.txt
jupyter notebook linear_probing.ipynb
```
