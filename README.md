## 👋

I build GPU kernels for LLM inference.

Currently exploring speculative decoding, attention variants, and the boundary between CUDA and Triton.

---

### 🔥 Pinned Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/shiloz-stack/VeloSpec">VeloSpec</a>
      </h3>
      <p align="center"><b>Grammar-aware adaptive speculative decoding</b></p>
      <p align="center">
        3 CUDA + 1 Triton kernel · 2.7× throughput on enum-heavy schemas<br>
        Adaptive K via free bitmask popcount · Benchmark on A100
      </p>
      <p align="center">
        <code>popcount_density.cu</code> 111× · <code>grammar_masked_argmax.cu</code> fused · <code>fused_sample.cu</code> online softmax
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">
        <a href="https://github.com/shiloz-stack/Flare">Flare</a>
      </h3>
      <p align="center"><b>From-scratch Triton attention kernels</b></p>
      <p align="center">
        FlashAttention v2 · MLA (DeepSeek) · KDA (Kimi)<br>
        No wrappers. Written from the algorithm — verified against PyTorch
      </p>
      <p align="center">
        MLA: <b>98.4%</b> KV cache reduction at 128K context
      </p>
    </td>
  </tr>
</table>

---

### 🛠 Stack

| | |
|---|---|
| **GPU** | CUDA · Triton · cuRAND · Nsight Compute |
| **ML** | PyTorch · HF Transformers · vLLM |
| **Lang** | Python · C++ · CUDA C |
| **Infra** | A100-SXM4 · Google Colab · GitHub Actions |

---

<a href="https://github.com/shiloz-stack">
  <img height="160" align="center" src="https://github-readme-stats.vercel.app/api?username=shiloz-stack&show_icons=true&theme=transparent&hide_border=true&count_private=true&hide_title=true" />
</a>
<a href="https://github.com/shiloz-stack">
  <img height="160" align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shiloz-stack&layout=compact&theme=transparent&hide_border=true&hide_title=true" />
</a>
