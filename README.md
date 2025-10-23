# Into the crossfire: evaluating the use of a language model to crowdsource gun violence reports

This repository contains the LaTeX source code and research materials for the paper "Into the crossfire: evaluating the use of a language model to crowdsource gun violence reports" by Adriano Belisario, Scott A. Hale, and Luc Rocher from the Oxford Internet Institute, University of Oxford.

## Compilation

To compile the paper:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Citation

- **Journal**: Proceedings of the ACM on Human-Computer Interaction
- **Volume**: 9, No. 7, CSCW235
- **Date**: November 2025
- **DOI**: [10.1145/3757416](https://doi.org/10.1145/3757416)

```bibtex
@article{10.1145/3757416,
author = {Belisario, Adriano and Hale, Scott A. and Rocher, Luc},
title = {Into the Crossfire: Evaluating the Use of a Language Model to Crowdsource Gun Violence Reports},
year = {2025},
issue_date = {November 2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {9},
number = {7},
url = {https://doi.org/10.1145/3757416},
doi = {10.1145/3757416},
abstract = {Gun violence is a pressing human rights issue that affects nearly every dimension of the social fabric, from healthcare and education to psychology and the economy. Reliable data on firearm events is paramount to developing more effective public policy and emergency responses. However, the lack of comprehensive databases and the risks of in-person surveys prevent human rights organizations from collecting needed data in most countries. Here, we partner with a Brazilian human rights organization to conduct a systematic evaluation of language models to assist with monitoring real-world firearm events from social media data. We propose a fine-tuned BERT-based model trained on Twitter (now X) texts to distinguish gun violence reports from ordinary Portuguese texts. We then incorporate our model into a web application and test it in a live intervention. We study and interview Brazilian analysts who continuously check social media texts to identify new gun violence events. Qualitative assessments show that our solution helped all analysts use their time more efficiently and expanded their search capacities. Quantitative assessments show that the use of our model was associated with analysts having further interactions with online users reporting gun violence. Our findings suggest that human-centered interventions using language models can help support the work of human rights organizations.},
journal = {Proc. ACM Hum.-Comput. Interact.},
month = oct,
articleno = {CSCW235},
numpages = {31},
keywords = {crowdsourcing, firearm violence, quantitative human rights, social media, text classification}
}
```

## Code and data

[https://github.com/belisards/gunviolence_ptbr](https://github.com/belisards/gunviolence_ptbr)

## Authors

- Adriano Belisario | [GitHub](https://github.com/belisards)
- Scott A. Hale | [GitHub](https://github.com/computermacgyver)
- Luc Rocher | [GitHub](https://github.com/cynddl)
