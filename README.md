# Xuan (Lily) Yang — academic website

A static website for GitHub Pages. Edit `index.html` for content and
`stylesheet.css` for presentation. No build step, JavaScript dependency,
external font request, or package installation is required.

## Preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8000.

## Content maintenance

- Keep the research positioning inside the introduction. A separate research
  directions section is intentionally omitted so news and papers appear sooner.
- Lead with Local Shapley and Batch-of-Thought, followed by the D-Shap preprint.
  Each paper keeps a full author list, publication status, a short contribution,
  and direct links. Earlier work remains visible below the recent papers.
- Update paper metadata, news, and experience dates together.
- Keep preprints explicitly labeled until acceptance is confirmed.
- `assets/xuanyang_cv.pdf` is the current CV, linked from `.profile-links`.
  It was supplied as `CV_XUAN_YANG Pro.pdf` and copied without changing its
  contents. Replace this asset when updating the CV so the public URL stays stable.
- Stylesheet and CV links have content-version query strings to refresh cached
  assets after deployment. Update these versions when replacing either asset.
- The page welcomes academic and industry research conversations. Add a dated
  2027 job-market announcement when the search is ready to be public.

## Sources checked during the redesign

- [Local Shapley](https://arxiv.org/abs/2603.03672): updated title and retraining guarantee.
- [Dynamic Shapley Computation](https://arxiv.org/abs/2605.20620): title, authors, and update costs.
- [Batch-of-Thought](https://arxiv.org/abs/2601.02950): authors and inference-cost result.
- [MPCEval](https://arxiv.org/abs/2603.04969): full author list and evaluation scope.
- [TUA-Bench](https://tuabench.ai/): authors, paper link, and benchmark scope.
- [AAAI awards](https://aaai.org/about-aaai/aaai-awards/aaai-conference-paper-awards-and-recognition/): DropMessage award.
- [Scientific Reports](https://www.nature.com/articles/s41598-023-30100-5): corrected publication year to 2023 and journal name.
- [RiseNet](https://arxiv.org/abs/2203.14807): restored two omitted coauthors.

EMNLP/VLDB/KDD acceptance news was retained from the existing website and is
consistent with the supplied CV. The current research extension to LLM data
curation and agent memory, expected graduation year, Google internship dates and
role, industry outcomes, teaching, and reviewing service come from the updated CV.
Stanford and NUS research visits were retained from the existing website.

## Layout references

The revision was informed by a visual review of these public personal sites;
their text, assets, and code were not copied:

- [Alexander Wettig](https://codecreator.github.io/): concise introduction and
  a scannable publication list; completed his Princeton PhD in 2026.
- [Niklas Muennighoff](https://muennighoff.com/): research results immediately
  follow the introduction, with a brief contribution for each project.
- [Yijia Shao](https://cs.stanford.edu/~shaoyj/): clear academic identity and
  direct access to publications and CV.
- [Zora Wang](https://zorazrw.github.io/): clear separation of identity,
  affiliations, news, and individual research outputs.
- [Xinran Zhao](https://colinzhaoust.github.io/): conventional academic typography
  and legible author/venue information.
