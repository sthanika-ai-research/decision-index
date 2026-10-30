# Submissions

| Board | Model | Hub repo | Results | Engine and options | Kit commit | Hardware | Resolution | Declared limits |
|---|---|---|---|---|---|---|---|---|
| **vision** | Sieve-31B-v3 | [sthanika-ai/Sieve-31B-v3](https://huggingface.co/sthanika-ai/Sieve-31B-v3/tree/8fcee858f7f20a50bfa3c8f984c22adb3cbb46a2) | [runs/Sieve-31B-v3-vision](https://huggingface.co/datasets/sthanika-ai/Sieve-31B-v3-vision-decision-index-results/tree/04f6f313244a40fa65bf6d682420764d005db697/runs/Sieve-31B-v3-vision) | [`decision_index_vision:SieveVision`](https://huggingface.co/sthanika-ai/Sieve-31B-v3/blob/8fcee858f7f20a50bfa3c8f984c22adb3cbb46a2/decision_index_vision.py) (in the model repo), `model=sthanika-ai/Sieve-31B-v3`, `--workers 1` | `f5a6e4f` | 1× A100 80GB PCIe, bf16 | Gemma 4 at 560 soft tokens per image (about 1.3 MP), after the kit's 1.6 MP cap | one question per request with images; up to 255 options; nothing truncated |
