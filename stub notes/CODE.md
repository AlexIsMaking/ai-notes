
2x coding speed https://github.blog/2022-09-07-research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/

## Data/Timeline

- Oct 2022: The Stack: 3 TB of permissively licensed source code in 30 programming languages https://huggingface.co/datasets/bigcode/the-stack
- Nov 2022: Kite.com public failure https://www.kite.com/blog/product/kite-is-saying-farewell/
  - Our diagnosis is that individual developers do not pay for tools. Their manager might, but engineering managers only want to pay for discrete new capabilities, i.e. making their developers 18% faster when writing code did not resonate strongly enough.
- Nov 2022: https://www.codeium.com/blog/beta-launch-announcement
- Dec 2022: reverse engineering copilot https://thakkarparth007.github.io/copilot-explorer/posts/copilot-internals.html#other-random-tidbits
- https://github.com/fauxpilot/fauxpilot This is an attempt to build a locally hosted version of [GitHub Copilot](https://copilot.github.com/). It uses the [SalesForce CodeGen](https://github.com/salesforce/CodeGen) models inside of NVIDIA's [Triton Inference Server](https://developer.nvidia.com/nvidia-triton-inference-server) with the [FasterTransformer backend](https://github.com/triton-inference-server/fastertransformer_backend/).
- Dec 2022: alphacode evaluation https://github.com/norvig/pytudes/blob/main/ipynb/AlphaCode.ipynb


## Known Issues

- Ryan Salva on how Copilot works + how to gain developer trust https://news.ycombinator.com/item?id=33226515
- https://medium.com/@enoch3712/github-copilot-is-under-the-hood-how-it-works-and-getting-the-best-out-of-it-4699d4dc3cd8
	- cushman - 2048 tokens
	- davinci - 4k tokens
- vulnerabilities https://www.spiceworks.com/it-security/security-general/news/40-of-code-produced-by-github-copilot-vulnerable-to-threats-research/
	- codex-davinci-002 [Do Users Write More Insecure Code with AI Assistants](https://arxiv.org/abs/2211.03622) some vulns found in C code with 75 participants - [media report](https://www.theregister.com/2022/12/21/ai_assistants_bad_code/)
	- codex-cushman-001 https://arxiv.org/abs/2208.09727
- Github Copilot investigation https://news.ycombinator.com/item?id=33240341
