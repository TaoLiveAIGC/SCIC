# SCIC: Scope- and Codebook-Aware Instruction Conditioning for Speaker-Adapted Expressive TTS

🎧 **[Demo Page](https://taoliveaigc.github.io/SCIC/)**

## Introduction

SCIC enables fine-grained, speaker-relative inline prosody control for expressive TTS. Inline instruction tags embedded in the text control the prosody of the following clause:

- `[pitch_up / pitch_down]` — Pitch ↑ / ↓
- `[energy_up / energy_down]` — Energy ↑ / ↓
- `[speed_up / speed_down]` — Speed ↑ / ↓
- `<sil_L1 ~ L3>` — Pause with increasing duration levels

SCIC combines a **Temporal Instruction Router** (frame-level tag activation) with **Tag-Specific Codebook Weighting** (per-tag strength across residual codebooks), and is further improved by multi-reward GDPO post-training.



## Contact

TaoLive-AIGC Team, Taobao & Tmall Group of Alibaba
