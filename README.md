# Exposing Blindspots: Cultural Bias Evaluation in Generative Image Models

**[Project Page](https://seochan99.github.io/ECB/)** | **[arXiv](https://arxiv.org/abs/2510.20042)** | **[Dataset](https://huggingface.co/datasets/seochan99/ecb-datasets)**

> We audit text-to-image and image-to-image models across six countries, combining automatic scores, a retrieval-augmented culture-aware metric, and native expert judgments to expose recurring cultural blindspots in generative image systems.

## Authors

**Huichan Seo**<sup>1*</sup>, **Sieun Choi**<sup>2*</sup>, **Minki Hong**<sup>2*</sup>, **Yi Zhou**<sup>1</sup>, **Junseo Kim**<sup>3</sup>, **Lukman Ismaila**<sup>4</sup>, **Naome Etori**<sup>5</sup>, **Mehul Agarwal**<sup>1</sup>, **Zhixuan Liu**<sup>1</sup>, **Jihie Kim**<sup>2</sup>, **Jean Oh**<sup>1</sup>

<sup>1</sup>Carnegie Mellon University · <sup>2</sup>Dongguk University · <sup>3</sup>Delft University of Technology · <sup>4</sup>Johns Hopkins University School of Medicine · <sup>5</sup>University of Minnesota Twin Cities · <sup>*</sup>Equal contribution

## Key Findings

- **Global-North defaults**: Country-agnostic prompts converge to U.S.-centric, modern aesthetics even with controlled schema and era cues.
- **Metric-human gap**: CLIPScore and aesthetic metrics remain stable while the culture-aware signal and native raters flag rapid semantic drift.
- **Shortcut editing**: Iterative I2I edits substitute palette shifts and flags for genuine cultural attributes, retaining source identity for Global-South targets.
- **Demographic skew**: Gender-neutral occupation prompts surface male dominance and light skin tones.

## Links

| Resource | Status |
|----------|--------|
| [Project Page](https://seochan99.github.io/ECB/) | Available |
| [arXiv](https://arxiv.org/abs/2510.20042) | Available |
| [Dataset](https://huggingface.co/datasets/seochan99/ecb-datasets) | Available |
| Code & Evaluation Assets | Coming Soon |

## Citation

```bibtex
@article{seo2025exposing,
  title={Exposing Blindspots: Cultural Bias Evaluation in Generative Image Models},
  author={Seo, Huichan and Choi, Sieun and Hong, Minki and Zhou, Yi and Kim, Junseo and Ismaila, Lukman and Etori, Naome and Agarwal, Mehul and Liu, Zhixuan and Kim, Jihie and Oh, Jean},
  journal={arXiv preprint arXiv:2510.20042},
  year={2025},
  url={https://arxiv.org/abs/2510.20042}
}
```

## Contact

`chans@andrew.cmu.edu`
