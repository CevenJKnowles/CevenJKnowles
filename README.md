# Ceven Jupiter Knowles

## Data Science & Workflows

Data scientist with a generalist's range: 26 years as an interdisciplinary designer leading creative and technical production for international clients, now applied to machine learning and AI systems.

Open to data science and applied machine learning roles, remote or hybrid from Berlin.

## Projects

**[LLTH | Liberated Local Thinking Harness](https://github.com/CevenJKnowles/LLTH)**
A free, open-source harness for running open-weight language models privately on a single consumer GPU, with no cloud and no subscription. Six models were benchmarked for speed and scored in a blind test of 20 prompts on a laptop with 6 GB of GPU memory, and differences under about 0.2 points are not treated as meaningful. One finding: a 7B model that fits on the card on paper generated 40 tokens per second with an empty context and 4 to 6 at 16K with default settings; tuning raised that to 18.6. Ten Architecture Decision Records govern the design and a documentation check runs in CI on every push. The interface, a local web page served by Python, is under construction.

**[KITTY3000-ML](https://github.com/CevenJKnowles/Kitty3000-ML)**
A classifier for ten categories of cat vocalisation, and a 2026 update of the 2018 CatSound paper. A CNN built from scratch in PyTorch (106k parameters) was set against two pretrained audio models, PANNs and AST. Looping with crossfades before chunking beat zero-padding by about 5.6 points, and testing at each clip's natural length removed an overstatement of about 2 points that windowed testing had produced. The CNN reached about 82% test accuracy against 83% for PANNs. An analytics dashboard (confusion matrix, UMAP, PCA, Grad-CAM) accompanies the models. One of two student projects selected as the final project of the Le Wagon bootcamp, built by a team of four with the designer as team lead.

**[I0³ | Deterministic AI Runtime](https://github.com/CevenJKnowles/io-iii-runtime)**
A local control plane for language models, built in Python, with a fixed routing table, bounded execution limits and 34 Architecture Decision Records. 1,182 tests run in CI. Latest stable: v1.0.0.

## Connect

* **Site:** https://cevenknowles.com (portfolio and knowledge site, [source](https://github.com/CevenJKnowles/cjk-knowledgehub))
* **LinkedIn:** https://www.linkedin.com/in/cevenknowles/
* **Substack:** https://substack.com/@cevenjupiterknowles
* **Behance:** https://www.behance.net/cevenknowles
* **Location:** Berlin, Germany
