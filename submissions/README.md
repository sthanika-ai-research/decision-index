# Submissions

| Board | Model | Hub repo | Results | Engine and options | Kit commit | Hardware | Resolution | Declared limits |
|---|---|---|---|---|---|---|---|---|
| **vision** | Sieve-Vision-27B | [sthanika-ai/Sieve-Vision-27B](https://huggingface.co/sthanika-ai/Sieve-Vision-27B/tree/1826ddd105cd3c34513fa5389ed82ee7569624b0) | [runs/Sieve-Vision-27B](https://huggingface.co/datasets/sthanika-ai/Sieve-Vision-27B-decision-index-results/tree/273f6a2ca75a772a4d377646898a0de89a2a7ded/runs/Sieve-Vision-27B) | [`sieve_vision_engine:SieveVisionEngine`](https://huggingface.co/sthanika-ai/Sieve-Vision-27B/blob/1826ddd105cd3c34513fa5389ed82ee7569624b0/sieve_vision/engine.py) (in the model repo), `model=sthanika-ai/Sieve-Vision-27B` | `f5a6e4f` | 1× A100 80GB PCIe, bf16 | native up to 1.6 MP per image (no lower cap) | none: any number of images and options; nothing truncated |
