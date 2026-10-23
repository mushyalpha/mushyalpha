<h1 align="center">Bonolo Masima</h1>
<h3 align="center">AI Inference Engineer · UK</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/bonolo-masima-093a6a147/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://bonolomasima.blog/"><img src="https://img.shields.io/badge/Blog-000000?style=for-the-badge&logo=hashnode&logoColor=white" alt="Blog"></a>
</p>

**Hey, I'm Bonolo 👋** I write GPU kernels.

- 🤖 Before that: robotics and embedded work, including NAO6 robot football controllers and a full build of an automated drink dispenser (APDS9960 gesture driver rewrite).

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=mushyalpha&show_icons=true&theme=dark&hide_border=true" alt="GitHub stats">
  <img height="165" src="https://streak-stats.demolab.com/?user=mushyalpha&theme=dark&hide_border=true" alt="GitHub streak">
</p>

## Pinned

<p>
<a href="https://github.com/mushyalpha/baby-vllm"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mushyalpha&repo=baby-vllm&theme=dark&hide_border=true" /></a>
<a href="https://github.com/mushyalpha/sglang"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mushyalpha&repo=sglang&theme=dark&hide_border=true" /></a>
<a href="https://github.com/mushyalpha/flashinfer"><img src="https://github-readme-stats.vercel.app/api/pin/?username=mushyalpha&repo=flashinfer&theme=dark&hide_border=true" /></a>
</p>

## Toolchain

<p>
<img src="https://img.shields.io/badge/CUDA-0d1117?style=for-the-badge&logo=nvidia&logoColor=39d353" />
<img src="https://img.shields.io/badge/TRITON-0d1117?style=for-the-badge" />
<img src="https://img.shields.io/badge/PYTORCH-0d1117?style=for-the-badge&logo=pytorch&logoColor=39d353" />
<img src="https://img.shields.io/badge/PYTHON-0d1117?style=for-the-badge&logo=python&logoColor=39d353" />
<img src="https://img.shields.io/badge/C%2B%2B-0d1117?style=for-the-badge&logo=cplusplus&logoColor=39d353" />
<img src="https://img.shields.io/badge/NSIGHT-0d1117?style=for-the-badge&logo=nvidia&logoColor=39d353" />
</p>

## Open Source Contributions

- **SGLang** · [#45844](https://github.com/sgl-project/sglang/pull/45844): stop Triton recompiling the DSA tiled decode kernel per page-table stride (do_not_specialize), with a regression test · *in review*

## Projects

| Project | Description |
|---|---|
| [baby-vllm](https://github.com/mushyalpha/baby-vllm) | vLLM-style inference engine from scratch: continuous batching (mixed prefill and decode), paged KV cache with preemption and recompute, a vLLM-like `LLM` / `SamplingParams` API, and a throughput benchmark against HuggingFace · matches vLLM 0.32.0 on H100 (Qwen2.5-7B): 168.0 vs 163.7 tok/s at batch 1, 1,239 vs 1,198 at batch 8 |
| [mistral7B-inference](https://github.com/mushyalpha/mistral7B-inference) | Running inference on Mistral 7B and comparing it with a baseline HuggingFace model |
| [day5-cuda-graphs](https://github.com/mushyalpha/day5-cuda-graphs) | CUDA graphs experiments (Python) |
| [miniOrca](https://github.com/mushyalpha/miniOrca) | Python project |
| [robotics-tdp-team1](https://github.com/mushyalpha/robotics-tdp-team1) | NAO6 robot football team (University of Glasgow): balance, fall-recovery and side-step controllers |
| [FlowFizzy](https://github.com/mushyalpha/FlowFizzy) | Automated drink dispenser (C++): APDS9960 gesture/proximity driver rewrite and memory-management refactor |
