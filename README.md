# RealFactBench

[![arXiv](https://img.shields.io/badge/arXiv-2506.12538-red)](https://arxiv.org/abs/2506.12538)

<p align="center"> 
<img src="figs/overview.png"/>
</p>
We introduce RealFactBench, a comprehensive benchmark designed to assess the fact-checking capabilities of LLMs and MLLMs across diverse real-world tasks, including
Knowledge Validation, Rumor Detection, and Event Verification. RealFactBench consists of 6K high-quality claims drawn from authoritative sources, encompassing multimodal content and diverse domains. The dataset could be found at [DATASET](https://huggingface.co/datasets/kalends/RealFactBench)

## Experiments

#### Main Results

<p align="center"> 
<img src="figs/main.png"/>
</p>

#### Results w.r.t. Web Search Tool

<p align="center"> 
<img src="figs/web.png"
     style="width: 50%; height: auto;"/>
</p>

#### Results w.r.t. Multimodal Input

<p align="center"> 
<img src="figs/multimodal.png"
     style="width: 50%; height: auto;"/>
</p>

#### Impact of Knowledge Cutoff

<p align="center"> 
<img src="figs/cutoff.png"
     style="width: 50%; height: auto;"/>
</p>

## Case Study

<p align="center"> 
<img src="figs/case.png"/>
</p>

## Citation

If you find our paper useful for your research, please consider giving a star :star: and citation :pencil: :)

```BibTeX
@inproceedings{yang2025realfactbench,
    title={RealFactBench: A Benchmark for Evaluating Large Language Models in Real-World Fact-Checking},
    author={Shuo Yang and Yuqin Dai and Guoqing Wang and Xinran Zheng and Jinfeng Xu and Jinze Li and Zhenzhe Ying and Weiqiang Wang and Edith C. H. Ngai},
    booktitle = {Proceedings of the 33nd ACM International Conference on Multimedia},
    year={2025}
}
```
