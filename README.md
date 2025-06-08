# Topic Modeling CS Papers

This project was my undergraduate senior thesis at Reed College, completed in May 2019. The goal was to build an unsupervised system to automatically classify academic papers from major computer systems conferences into meaningful research subfields — without relying on pre-existing labels.

## Summary

Using a corpus of 2,500+ CS papers, the project applied:

- **Latent Dirichlet Allocation (LDA)** to extract latent topic distributions
- **k-means clustering** to form subfields based on topic vectors
- **TF-IDF encoding** and **bag-of-words** as alternative baselines
- Evaluation against human-generated categories from conference metadata

The classifier successfully reconstructed recognizable research areas such as networking, databases, security, and cloud systems — demonstrating the feasibility of topic modeling for organizing academic literature.

## Tools Used

- Python, scikit-learn, gensim, matplotlib, NLTK
- Manual preprocessing of PDF corpora from SIGCOMM, OSDI, NSDI, and other conferences

## Status

This repo is currently a placeholder. Code and cleaned data may be added in the future, pending licensing and cleanup.

## Contact

📫 Reach me at `tanmay [dot] dubey [dot] nine five one four [at] gmail [dot] com`  
🔗 Also see my LinkedIn: [linkedin.com/in/tanmay-dubey](https://linkedin.com/in/tanmay-dubey)
