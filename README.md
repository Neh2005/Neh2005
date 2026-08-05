## Neha Ann Binoy

I build AI systems for healthcare that clinicians can actually trust — and the engineering underneath them, from research pipelines to the tools that ship. Right now that means multimodal clinical AI at DiceMed and a research paper under review at MICCAI 2026.

**Currently**
- Final-year CS (Best Graduating Student, First Class) — Coventry University, graduating June 2026
- ML Research Intern at DiceMed — building a BiomedCLIP-based system that flags inconsistencies between dental CBCT scans and clinical notes
- Co-author, ODIN Workshop @ MICCAI 2026 — *Multimodal Clinical-Data-Integrity for Dental CBCT* (under review)

---

### Selected work

**[Trustworthy AI for ECG Anomaly Detection](https://github.com/Neh2005/Trustworthy-ECG-Anomaly-Detection-Dissertation)**
Compared CNN, ResNet, and a Hybrid Transformer-CNN on MIT-BIH — not just for accuracy, but for whether their explanations (Grad-CAM, Integrated Gradients) held up under adversarial attack (FGSM, PGD). The simplest model won on all three fronts: 97% accuracy, 0.87 macro-F1, and the most stable explanations under attack. Complexity ≠ trust.

**[Diabetes Risk — Deep Learning vs. Ensembles](https://github.com/Neh2005/Hybrid-Deep-Learning-Ensemble-Diabetes-Predictor)**
Benchmarked CNN-RNN and Transformer-CNN hybrids against XGBoost, LightGBM, and CatBoost on ~195K CDC health records. A stacking ensemble beat every neural model I tried — 0.907 accuracy, 0.964 AUC vs. 0.831 for the best deep model. Sometimes the boring model is the right one.

**[Komodo Hub](https://github.com/Neh2005/Komodo-Hub---University-Team-project)**
Real-time collaboration platform — led a 6-person team through RBAC, live messaging, and a GitHub Actions pipeline that deploys to Firebase on every commit. Stress-tested to 100 concurrent sessions.

**[Secure E-Commerce Platform](https://github.com/Neh2005/Secure-E-Commerce-project)**
Built it, then spent as much time trying to break it — OWASP Top 10 hardening, MFA, and an automated audit pipeline (Bandit, Semgrep, ZAP) that ran on every commit until it reached zero exploitable vulnerabilities.

*(+ [genomic-variant-density-viewer](https://github.com/Neh2005/genomic-variant-density-viewer) — Rust/WASM, and [Healio](https://github.com/Neh2005/Healio_Microsoft_Imagine_Cup) — Microsoft Imagine Cup)*

---

### Stack

- **ML / research** — PyTorch, TensorFlow, Scikit-learn, XGBoost/LightGBM/CatBoost, BiomedCLIP, Grad-CAM & Integrated Gradients, adversarial training (FGSM/PGD)
- **Backend / data** — Python, Django, Flask, SQL, Pandas, Firebase
- **Web** — React, Node.js, REST APIs
- **Shipping** — Git, GitHub Actions CI/CD, Docker, OWASP-aligned security practice

---

Reach me: **[neha.ann.binoy@gmail.com](mailto:neha.ann.binoy@gmail.com)**
