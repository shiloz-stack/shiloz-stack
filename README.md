<div align="center">

### GPU Kernel Engineer · LLM Systems

Building CUDA & Triton kernels for inference at the edge of what GPUs can do.

</div>

---

<table>
<tr>
<td width="50%">

### [VeloSpec](https://github.com/shiloz-stack/VeloSpec)
**Grammar-aware speculative decoding**

3 CUDA + 1 Triton kernel. Adaptive K via bitmask popcount.

`popcount_density` **111×** · `grammar_argmax` fused · `fused_sample` online softmax

**2.7×** throughput on enum-heavy schemas · A100-SXM4

</td>
<td width="50%">

### [Flare](https://github.com/shiloz-stack/Flare)
**From-scratch Triton attention kernels**

FlashAttention v2 · MLA (DeepSeek) · KDA (Kimi)

No wrappers — tiling, online softmax, recurrent state, written from the algorithm.

MLA: **98.4%** KV cache reduction at 128K context

</td>
</tr>
</table>

---

<div align="center">

`CUDA` · `Triton` · `PyTorch` · `C++` · `Python` · `Nsight Compute` · `A100`

</div>
