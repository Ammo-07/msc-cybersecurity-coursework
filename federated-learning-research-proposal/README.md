Federated Learning for Privacy-Preserving Healthcare AI — Research Proposal

MSc Cybersecurity coursework, University of York. A 3-minute academic research-pitch presentation proposing a federated learning approach to privacy-preserving disease prediction across hospitals.

What this is

This is a research proposal, not a completed implementation or experiment. The exercise was to design and pitch a well-scoped research project within a fixed time constraint — the topic, methodology, and framing were chosen independently. Figures shown in the presentation are explicitly labelled as illustrative projections, not experimental results.

The proposal

Hospitals hold sensitive patient data that UK GDPR and the Data Protection Act 2018 prevent them from pooling, yet reliable disease-prediction models need large, diverse datasets to generalise well. Traditional centralised machine learning requires pooling that data, creating an unavoidable conflict between building powerful diagnostic tools and protecting patient privacy.

The proposed approach is federated learning: each hospital trains a model on its own local data, and only model updates — never patient records — are shared with a central server that aggregates them into an improved shared model. The proposal sets out a fair, controlled comparison: a centralised baseline versus a federated approach, trained on the same two public healthcare benchmarks (UCI Heart Disease, Pima Indians Diabetes) under identical conditions, using TensorFlow Federated.

Proposed 24-week plan:

Phase	Weeks	Focus
Literature review	1–4	Survey federated learning and disease-prediction research; select datasets and methods
Data preparation	5–8	Clean and partition the two datasets across five simulated hospital nodes
Model development	9–17	Implement centralised and federated models under identical conditions
Evaluation & analysis	18–22	Compare on accuracy, F1-score, communication cost, and privacy risk (membership inference resistance)
Finalisation & writing	23–24	Write up findings; prepare for academic submission; open-source release

Proposed (not yet demonstrated) expected outcome: federated accuracy within roughly 5% of the centralised baseline, with no raw patient data ever exposed — privacy quantified via resistance to membership inference attacks and differential-privacy bounds (ε, δ).

Why this is relevant

Beyond the specific topic, the exercise this demonstrates is communicating a technical privacy/security trade-off clearly, to a non-specialist audience, under a hard time constraint — the same skill needed to pitch a privacy-by-design control, an access-governance change, or a security investment case to stakeholders who aren't security specialists themselves.

Contents
presentation.pptx — the slide deck (8 slides)
script.docx — the full spoken narration script
