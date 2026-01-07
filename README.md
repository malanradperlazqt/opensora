# OpenSora

> **Open-source, locally runnable video generation from text — inspired by Sora, built for everyone.**  
> Generate coherent, cinematic videos from natural language prompts — **100% offline, no cloud, no paywall.**

OpenSora brings state-of-the-art text-to-video synthesis to your desktop. Trained on open datasets and built with transparent architecture, it empowers creators, researchers, and developers to explore the future of generative media — **without dependency on closed APIs or corporate infrastructure.**

<p align="center">
  <img src="https://placehold.co/640x360/0f172a/ffffff?text=A+dragon+flying+over+ancient+mountains+at+dawn" width="31%" />
  <img src="https://placehold.co/640x360/1e293b/ffffff?text=Underwater+city+with+bioluminescent+corals" width="31%" />
  <img src="https://placehold.co/640x360/020617/ffffff?text=Futuristic+Tokyo+street+in+heavy+rain" width="31%" />
</p>

---

## Why OpenSora?

While commercial video models remain closed, **OpenSora is open by design**:

- ✅ **Fully local** — runs on your machine (GPU or CPU)  
- ✅ **Open weights & training data** — audit, fine-tune, extend  
- ✅ **Community-driven** — no gatekeeping, no secrets  
- ✅ **Ethical by default** — built with responsible AI principles  
- ✅ **Interoperable** — integrates with Hugging Face, ComfyUI, and more  

This is not just a model — it’s a **movement toward open generative media**.

---

## Quick Start

## Features

- Text-to-video generation (2–16 seconds)
- Support for image + text conditioning (img2video)
- Resolution up to 1024×576 (progressive generation)
- Batch processing & seed control
- Export to MP4, GIF, or frame sequences
- Built-in safety filter (toggle on/off)

## Performance (4-second video)

| Hardware        | Resolution   | Time     |
|-----------------|--------------|----------|
| RTX 4090        | 512×512      | ~2 min   |
| RTX 3090        | 384×384      | ~4 min   |
| Apple M2 Max    | 256×256      | ~6 min   |
| CPU (16-core)   | 256×256      | ~45 min  |

Use `--low-vram` or `--fp16` for memory-constrained systems.

## Project Vision

OpenSora is more than code — it’s a commitment to:

- Open access to foundational generative models
- User sovereignty over data and output
- Global collaboration in AI development
- Education and research without barriers

We believe the future of AI must be open, local, and human-centered.

## License

Model weights: OpenRAIL-M  
Code: MIT License  
Training data: LAION-OpenVid + WebVid-Open (filtered, CC-licensed)

See `LICENSE` and `MODEL_LICENSE` for details.

## Join the Movement

- Star the repo to show support
- Report issues or request features
- Contribute models, UI improvements, or documentation
- Share your creations with `#OpenSora`

The future of video is open. Build it with us.

OpenSora: Where imagination becomes motion — freely, locally, and responsibly.
