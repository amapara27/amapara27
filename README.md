## Aayan Mapara

currently working on ai tools, exploring inference, and researching ml systems + compilers. 
check out my projects below, but also head to <a href="https://aayanmapara.com"/>my website</a> to learn more about me.

<table>
<tr>
<td width="50%" valign="top">

<h3>GPU kernels</h3>
<sub><i>CUDA C++ · FP16 · Nsight Compute</i></sub>

<p>CUDA kernels written from scratch, each checked against a reference and profiled.</p>

<ul>
<li><a href="https://github.com/amapara27/flash-attention">FlashAttention-2 forward</a>: 2.66 ms at N=4096, d=64 (4 heads), 6.8× faster than my first multi-head version</li>
<li><a href="https://github.com/amapara27/sgemm">SGEMM</a>: 90.9% of cuBLAS on 4096×4096 matrices</li>
<li><a href="https://github.com/amapara27/cuda-reductions">Reductions</a>: a progression of CUDA reduction kernels, built before FA2</li>
</ul>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/amapara27/anchor">Anchor</a></h3>
<sub><i>Rust · Tauri · React · Ollama · MLX</i></sub>

<p>find, fit, and benchmark local models on Apple Silicon.</p>

<ul>
<li>tells you whether a model fits your Mac before you download it</li>
<li>measures decode speed and time to first token on Ollama or MLX, in a desktop app and a CLI</li>
</ul>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3><a href="https://github.com/amapara27/jev-pilot">Jev Pilot</a></h3>
<sub><i>Python · Nemotron Speech · Jev</i></sub>

<p>control your Mac with spoken commands.</p>

<ul>
<li>transcribes speech locally, then Jev picks a grounded action</li>
<li>checks each result before continuing to the next command</li>
<li>300+ PyPI downloads (excluding mirrors)</li>
</ul>

</td>
<td width="50%" valign="top">

<h3><a href="https://github.com/amapara27/scribeshield">ScribeShield</a></h3>
<sub><i>Python · PyTorch · Whisper (LoRA) · FastAPI</i></sub>

<p>healthcare phone-call transcription that flags uncertain words and corrects only with evidence.</p>

<ul>
<li>1st place at VillageHacks 2026; led a team of four and built the fine-tuned model and serving backend</li>
<li>LoRA fine-tuned Whisper Small: 4.14% word error rate on a synthetic telephony benchmark (commercial baseline: low 20s%)</li>
</ul>

</td>
</tr>
</table>

Also: [Recon](https://github.com/amapara27/recon-ethereum-security), live Ethereum fraud detection and contract auditing.
