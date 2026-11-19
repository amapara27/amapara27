## Aayan Mapara

currently working on ai tools, exploring inference, and researching ml systems + compilers.  //
check out my projects below, but also head to <a href="https://aayanmapara.com"/>my website</a> to learn more about me.

## Projects
<table>
<tr>
<td width="50%" valign="top">

GPU Kernels //
<sub><i>CUDA · C++ · FP16 · Nsight Compute · Nsight Systems</i></sub>

CUDA kernels written from scratch, each checked against a reference and profiled.

- [FlashAttention-2](https://github.com/amapara27/flash-attention): 2.66 ms at N=4096, d=64 (4 heads), 6.8× faster than my first version
- [SGEMM](https://github.com/amapara27/sgemm): 90.9% of cuBLAS performance on 4096×4096 matrices
- [Reductions](https://github.com/amapara27/cuda-reductions): a progression of CUDA reduction kernels, built before FA2

</td>
<td width="50%" valign="top">

[Anchor](https://github.com/amapara27/anchor) //
<sub><i>Rust · Tauri · React · Ollama · MLX</i></sub>

find, fit, and benchmark local models on Apple Silicon.

- tells you whether a model fits your Mac before you download it
- measures decode speed and time to first token on Ollama or MLX, in a desktop app and a CLI

</td>
</tr>
<tr>
<td width="50%" valign="top">

[Jev Pilot](https://github.com/amapara27/jev-pilot) //
<sub><i>Python · Nemotron Speech · Jev</i></sub>

control your Mac with spoken commands. 300+ downloads 

- transcribes speech locally, then Jev picks a grounded action
- checks each result before continuing to the next command

</td>
<td width="50%" valign="top">

[ScribeShield](https://github.com/amapara27/scribeshield) //
<sub><i>Python · PyTorch · Whisper (LoRA) · FastAPI</i></sub>

healthcare phone-call transcription that flags uncertain words and corrects only with evidence.

- 1st place at VillageHacks 2026; I led a team of four and built the fine-tuned model and serving backend
- LoRA fine-tuned Whisper Small: 4.14% word error rate

</td>
</tr>
</table>
