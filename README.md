# MIT Introduction to Deep Learning — Lab Solutions

My completed solutions to the software labs from **[MIT 6.S191: Introduction to Deep Learning](http://introtodeeplearning.com)**, based on the official course repository: [MITDeepLearning/introtodeeplearning](https://github.com/MITDeepLearning/introtodeeplearning).

> ⚠️ These are my personal, worked-through versions of the labs (all `#TODO` cells filled in), kept here for my own reference and portfolio.

## About the course

MIT 6.S191 is MIT's introductory course on deep learning, covering foundational algorithms and hands-on labs in areas like computer vision, sequence modeling, generative models, and reinforcement/large language models. Lecture slides and videos are freely available on the [course website](http://introtodeeplearning.com).

## Repository structure

```
.
├── lab1/         # Lab 1 solution(s)
├── lab2/         # Lab 2 solution(s)
├── lab3/         # Lab 3 solution(s)
├── xtra_labs/    # Optional/extra labs (if attempted)
└── README.md
```

Each `labX/` folder mirrors the structure of the original course repo and contains the completed Jupyter notebook(s) (`*.ipynb`), plus any supporting files or outputs generated while working through the exercises.

> 📝 Update the table below with the specific topic of each lab, since these can change from year to year in the official repo.

| Lab | Topic | Notebook |
|-----|-------|----------|
| Lab 1 | *e.g. Intro to TensorFlow/PyTorch & Music Generation (RNN)* | [`lab1/`](./lab1) |
| Lab 2 | *e.g. Computer Vision (CNNs, facial detection/debiasing)* | [`lab2/`](./lab2) |
| Lab 3 | *e.g. Reinforcement Learning / LLMs* | [`lab3/`](./lab3) |
| Xtra | *Optional bonus labs* | [`xtra_labs/`](./xtra_labs) |

## Running the notebooks

These labs are designed to run in **Google Colab**:

1. Open the notebook you want (`.ipynb`) directly on GitHub.
2. Click the **"Open in Colab"** badge at the top of the notebook (or open it manually via [colab.research.google.com](https://colab.research.google.com) using this repo's URL).
3. In Colab, go to **Runtime → Change runtime type** and select **GPU** as the hardware accelerator.
4. Run the cells top to bottom.

The labs rely on the official `mitdeeplearning` helper package:

```bash
pip install mitdeeplearning
```

```python
import mitdeeplearning as mdl
```

## Credits & license

All original lab content, starter code, and materials are © MIT Introduction to Deep Learning, created by the 6.S191 course staff, and are licensed under the terms in the [original repository](https://github.com/MITDeepLearning/introtodeeplearning/blob/master/LICENSE.md). This repo only contains my own completed versions of the exercises, for personal learning and reference.

> © MIT Introduction to Deep Learning — <http://introtodeeplearning.com>
