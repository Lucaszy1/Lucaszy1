## Hi, I'm Luca 

Computer Science student at **Cal Poly San Luis Obispo**, focused on **cybersecurity**, applied **machine learning**, and the ethical side of AI development.

I like building complete systems end to end, from the detection logic to the dashboard someone actually uses, and I care about understanding *why* something works rather than just getting it to run.

### What I'm working on

**[Crucible](https://github.com/Lucaszy1/Crucible)** is a simulated range where AI defenders practice containment judgment. Two AI teams play out an exercise on a toy company network, one probing for a way in and the other watching logs and deciding what to shut down, while a separate model audits every defensive decision against the evidence the defender actually had. Every move is logged, so any run can be replayed and scored. I built it solo for Meta's Global AI Developer Hackathon, and the results come with their limits stated plainly, including a first campaign I threw out after catching a bug in my own test setup.

**[Alibi](https://github.com/Lucaszy1/Alibi)** is a provenance-aware adjudicator for AI coding agents. When endpoint security flags something an agent did, Alibi decides whether you actually asked for it or whether it traces back to an injected instruction hidden in a web page, file, or tool output, and returns a clear verdict: justified, unjustified, or hijacked. The core is fully deterministic and never runs the actions it judges, with a tiered pipeline spanning provenance, taint tracking, MITRE-mapped policy, and anomaly detection, plus homoglyph and leetspeak normalization to catch obfuscated prompt injection.

**[RansomwareAudit](https://github.com/Lucaszy1/RansomwareAudit)** is an independent ransomware detection tool combining entropy analysis, behavioral monitoring, permission auditing, and an unsupervised ML model, with an encrypted quarantine vault, real-time monitoring, a web dashboard, and a full test and evaluation harness.

**[Ultron](https://github.com/Lucaszy1/Ultron)** is a configurable AI bookkeeping assistant for QuickBooks that parses, validates, and reconciles messy spreadsheet exports for sales orders, item codes, inventory, and duplicates, with fuzzy column auto-mapping and a swappable business config so it adapts to any inventory-based business.

**[Hindsight](https://github.com/Lucaszy1/Hindsight)** is a human-in-the-loop annotation and active-learning pipeline. I rate AI chatbot conversations, store the annotations in MongoDB (documents, indexes, aggregation pipelines), train a scikit-learn classifier on the labels, and compare uncertainty sampling against random sampling, with the results documented honestly on a small sample.

### Tech I work with

`Python` · `JavaScript` · `SQL` · `Bash` · `Flask` · `scikit-learn` · `SQLite` · `Docker` · `Git` · `Chart.js` · `REST APIs` · `MongoDB` . 'Linux

### A bit more

Interested in security research, anomaly detection, and data labeling for ML. Comfortable working independently in remote, project-based settings. Outside of code, I do stand-up comedy and sail with the Sea Scouts, both of which keep me quick on my feet and clear when I communicate.

### Reach me

**Email:** lucaszy08@gmail.com  
**LinkedIn:** [linkedin.com/in/luca-szyszkowski-2a8832432](https://www.linkedin.com/in/luca-szyszkowski-2a8832432)
