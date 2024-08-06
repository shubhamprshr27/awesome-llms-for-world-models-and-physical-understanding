
<div align="center">
  Awesome LLMs for World Models and Physical Understanding
  <br />
  <a href="#about"><strong>Explore the docs »</strong></a>
  <br />
  <br />
  <!-- <a href="https://github.com/shubhamprshr27/awesome-llms-for-world-models-and-physical-understanding/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+">Report a Bug</a> -->
  <!-- · -->
  <!-- <a href="https://github.com/shubhamprshr27/awesome-llms-for-world-models-and-physical-understanding/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+">Request a Feature</a> -->
  <!-- . -->
  <!-- <a href="https://github.com/shubhamprshr27/awesome-llms-for-world-models-and-physical-understanding/issues/new?assignees=&labels=question&template=04_SUPPORT_QUESTION.md&title=support%3A+">Ask a Question</a> -->
</div>

<details open="open">
<summary>Topics covered</summary>

- [About](#about)
- [World Models](#world-models)
- [Large Language Models for World Understanding](#large-language-models-for-world-understanding)
- [Multimodal Generative World Models](#multimodal-generative-world-models)
- [Benchmarks](#benchmarks)
- [Miscellaneous](#miscellaneous)
- [Acknowledgement](#acknowledgement)
- [Contributing](#contributing)
- [Authors \& contributors](#authors--contributors)
- [License](#license)
</details>

---

## About

<table><tr><td>

With the recent success of Large Language Models (LLMs) in Natural Language Understanding (NLU) and Natural Language Generation (NLG) tasks, there is growing interest in evaluating their capabilities beyond traditional NLP applications. One key area of exploration is assessing how well LLMs understand the world around us (can LLMs act as world models?). This understanding enables the use of LLMs for general planning and physical reasoning tasks. Below, you'll find a curated list of papers and code repositories focused on this topic.



</td></tr></table>

<!-- ### Built With

> **[?]**
> Please provide the technologies that are used in the project. -->

## World Models

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| World Models | [arXiv](https://arxiv.org/abs/1803.10122) | -- | NeurIPS Oral | 27 Mar 2018 | [project page](https://worldmodels.github.io) |
| Learning to Model the World with Language | [arXiv](https://arxiv.org/abs/2308.01399) | [GitHub](https://github.com/jlin816/dynalang) | ICML Oral | 31 May 2024 | [project page](https://dynalang.github.io/) |
| Mastering Memory Tasks with World Models | [arXiv](https://arxiv.org/abs/2403.04253) | [GitHub](https://github.com/chandar-lab/Recall2Imagine) | ICLR Oral | 7 Mar 2024 |  |
| [Dreamer-V3] Mastering Diverse Domains through World Models | [arXiv](https://arxiv.org/abs/2301.04104) | [GitHub](https://github.com/danijar/dreamerv3) | arxiv | 10 Jan 2023 | [project page](https://danijar.com/project/dreamerv3/) |

## Large Language Models for World Understanding

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
| Language Models Meet World Models: Embodied Experiences Enhance Language Models | [arXiv](https://arxiv.org/abs/2305.10626) | [GitHub](https://github.com/szxiangjn/world-model-for-language-model) | NeurIPS | 28 Oct 2023 |  |
| Evaluating the World Model Implicit in a Generative Model | [arXiv](https://arxiv.org/abs/2406.03689)| -- | arXiv | 22 Jun 2024 | |
| Reasoning with Language Model is Planning with World Model | [arXiv](https://aclanthology.org/2023.emnlp-main.507.pdf)| [GitHub](https://github.com/Ber666/RAP) | EMNLP | 23 Oct 2023 | |
| Leveraging Pre-trained Large Language Models to Construct and Utilize World Models for Model-based Task Planning | [arXiv](https://arxiv.org/abs/2305.14909) | [GitHub](https://github.com/GuanSuns/LLMs-World-Models-for-Planning) | NeurIPS | 2 Nov 2023 | [project page](https://guansuns.github.io/pages/llm-dm/) |
| Can Language Models Serve as Text-Based World Simulators? | [arXiv](https://arxiv.org/abs/2406.06485) | -- | -- | 10 Jun 2024 | |
| Emergent World Representations: Exploring a Sequence Model Trained on a Synthetic Task | [arXiv](https://arxiv.org/abs/2210.13382) | [GitHub](https://github.com/likenneth/othello_world) | ICLR Top 5% | 26 Jun 2024 | |
| From Word Models to World Models: Translating from Natural Language to the Probabilistic Language of Thought | [arXiv](https://arxiv.org/abs/2306.12672) | [GitHub](https://github.com/gabegrand/world-models) | arXiv | 23 Jun 2023 | [Youtube - Wong and Gabriel](https://www.youtube.com/watch?v=XCs8qMRr7l8) [YouTube - Josh](https://www.youtube.com/watch?v=mvDxzmMpvl8)|
| Learning adaptive planning representations with natural language guidance | [arXiv](https://arxiv.org/abs/2312.08566) | -- | ICLR | 13 Dec 2023 |  |

## Multimodal Generative World Models 
| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
|Pandora: Towards General World Model with Natural Language Actions and Video States| [arXiv](https://arxiv.org/abs/2406.09455) | [GitHub](https://github.com/maitrix-org/Pandora?tab=readme-ov-file) | arXiv | 12 Jun 2024 | |
|Learning Interactive Real-World Simulators | [arXiv](https://arxiv.org/abs/2310.06114) | -- | ICLR outstanding paper | 13 Jan 2024 | [project page](https://universal-simulator.github.io/unisim/) |


## Benchmarks
| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
|Compositional 4D Dynamic Scenes Understanding with Physics Priors for Video Question Answering| [arXiv](https://arxiv.org/abs/2406.00622) | -- | arXiv | 2 Jun 2024 | |
|ContPhy: Continuum Physical Concept Learning and Reasoning from Videos| [arXiv](https://arxiv.org/abs/2402.06119) | [GitHub](https://github.com/zzcnewly/ContPhy-Gen) | ICML | 9 Feb 2024 | [project page](https://physical-reasoning-project.github.io/) |
|STAR: A Benchmark for Situated Reasoning in Real-World Videos| [arXiv](https://arxiv.org/abs/2405.09711) | [GitHub](https://github.com/csbobby/STAR_Benchmark) | NeurIPS | 2021 | |
|MM-Vet: Evaluating Large Multimodal Models for Integrated Capabilities| [arxiv](https://arxiv.org/pdf/2308.02490) | [GitHub](https://github.com/yuweihao/MM-Vet) | ICML 2024 | 4 Aug 2023 | |
|OpenEQA: From word models to world models| [Paper](https://open-eqa.github.io/assets/pdfs/paper.pdf) | [GitHub](https://github.com/facebookresearch/open-eqa) | Preprint | 2024 | [project page](https://open-eqa.github.io/assets/pdfs/paper.pdf), [Meta blog](https://ai.meta.com/blog/openeqa-embodied-question-answering-robotics-ar-glasses/)|
|CityBench: Evaluating the Capabilities of Large Language Model as World Model| [arXiv](https://arxiv.org/abs/2406.13945)| -- | arXiv | 20 Jun 2024 | |


## Miscellaneous

| Paper | Link | Code | Venue | Date | Other |
|-------|------|------|-------|------|-------|
|OpenVLA: An Open-Source Vision-Language-Action Model | [arXiv](https://arxiv.org/abs/2406.09246) | [GitHub](https://github.com/openvla/openvla) | arXiv | 13 Jun 2024 | [project page](https://openvla.github.io/)|
|Language Agent Tree Search Unifies Reasoning Acting and Planning in Language Models | [arXiv](https://arxiv.org/abs/2310.04406) | [GitHub](https://github.com/lapisrocks/LanguageAgentTreeSearch) | ICML | 06 Oct 2023 | |
|Building Cooperative Embodied Agents Modularly with Large Language Models| [arXiv](https://arxiv.org/abs/2307.02485)| [GitHub](https://github.com/UMass-Foundation-Model/Co-LLM-Agents) | ICLR | 05 Jul 2023 | [project page](https://vis-www.cs.umass.edu/Co-LLM-Agents/)|
|True Knowledge Comes from Practice: Aligning LLMs with Embodied Environments via Reinforcement Learning| [arxiv](https://arxiv.org/pdf/2401.14151) | [GitHub](https://github.com/WeihaoTan/TWOSOME) | ICLR | 25 Jan 2024 | |

## Acknowledgement


If you want to say **thank you** or/and support active development of Awesome LLMs for World Models and Physical Understanding:

- Add a [GitHub Star](https://github.com/shubhamprshr27/awesome-llms-for-world-models-and-physical-understanding) to the project.
- Tweet about the Awesome LLMs for World Models and Physical Understanding.
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

Together, we can make Awesome LLMs for World Models and Physical Understanding **better**!

## Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.


## Authors & contributors

The original setup of this repository is by [Shubham Parashar](https://github.com/shubhamprshr27).

For a full list of all authors and contributors, see [the contributors page](https://github.com/shubhamprshr27/awesome-llms-for-world-models-and-physical-understanding/contributors).

<!-- ## Security

Awesome LLMs for World Models and Physical Understanding follows good practices of security, but 100% security cannot be assured.
Awesome LLMs for World Models and Physical Understanding is provided **"as is"** without any **warranty**. Use at your own risk.

_For more information and to report security issues, please refer to our [security documentation](docs/SECURITY.md)._ -->

## License

This project is licensed under the **MIT license**.

See [LICENSE](LICENSE) for more information.

