# Hi, I'm Amanda! <img src="https://emojis.slackmojis.com/emojis/images/1536351075/4594/blob-wave.gif" width="25"/>
I'm a wet-lab turned computational biologist passionate about creating intuitive data visualizations for communities.

👩🏻‍🔬 PhD discovering molecular glues with cell images @ Georg Winter lab, Austria<br>
👩🏻‍🎓 Majored in Life Sciences + USP + SPS @ National University of Singapore, Singapore<br>
🌱 Growing my [digital garden](https://tangentialalmond.cc/), learning ML/DL and pursuing pet projects

# 💻 Tech Stack
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![R](https://img.shields.io/badge/r-%23276DC3.svg?style=flat&logo=r&logoColor=white) ![Julia](https://img.shields.io/badge/-Julia-9558B2?style=flat&logo=julia&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=flat&logo=gnu-bash&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=flat&logo=render&logoColor=white) ![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=flat&logo=daisyui&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white)

# 🤩 Featured Projects
## 🌱 [TeaDex](https://github.com/TangentialAlmond/teadex/tree/version1)
One of my hobbies is learning about teas produced around the world. With over 2000+ recorded cultivars of tea and a myriad of tea production procedures, I want to create a platform allowing the tea community to collaboratively catalog images of dry tea leaf and some basic information on them (e.g. name of the tea, tea type, production steps). This project is my first full-stack project and introduction to JavaScript. I have some major changes planned to streamline the development of TeaDex.
- **The Challenge:** How to visualize multi-modal data (images and processing parameters) for a specialized community?<br/>
- **The Solution:** A MERN-based platform utilizing AWS S3 for image serving and a clean, user-centric `React` interface.
- **Deployed at:** The public-client (read-only) of TeaDex is live at [https://teadex.onrender.com/](https://teadex.onrender.com/). There is, however, an external dependency bug which results in a server error. As I'm planning a stack overhaul to supabase + vercel, I won't be fixing this bug. Instead, you'll see a new website. 😉

## 🎨 [Isogenic Cell Painting Assay](https://github.com/GWinterLab/IsogenicCPA)
Molecular glues are a relatively new class of small-molecule drugs that gained traction in drug discovery around the 2020s. They "glue" together two proteins, creating a protein-drug-protein sandwich. This mechanism of action distinguishes molecular glues from other small-molecule drugs which typically form protein-drug complexes. Given this unique mechanism of action, new drug discovery assays are required to identify these molecular glues, and my colleagues and I at the [Georg Winter lab](https://www.winter-lab.com/) wondered if we could use images of cells treated with drugs to develop a novel molecular glue finding assay.
- **The Challenge:** Can morphological features from cell images be used to identify drug treatments with molecular glue behavior?
- **The Solution:** We adapted the [Cell Painting Assay](https://pmc.ncbi.nlm.nih.gov/articles/PMC5223290/) for finding molecular glues.
  - Implementation of a HPC-compatible pipeline: Built a pipeline using `cellpose` for whole-cell and nuceli segmentation, and `CellProfiler` for extracting > 1000 morphological features from 10000+ images of cells.
  - Multivariate exploration: Use of PCA, UMAP, correlation modelling (Kendall's $\tau_b$), and network visualization with `networkx` to distill biological "noise" into clear patterns identifying drugs that behave as molecular glues.
- **Published at:** [https://pubs.acs.org/doi/10.1021/acschembio.3c00598](https://pubs.acs.org/doi/10.1021/acschembio.3c00598)

<!-- Profile drafted with GPRM ( https://gprm.itsvg.in ) -->
