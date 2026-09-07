Human Error & AI-Generated Risk Assessment — Case Study

MSc Cybersecurity coursework, University of York. Applied human-error and risk-assessment frameworks to a real interactive system, and used generative AI to draft — then critically evaluate — a professional risk assessment for a fictional ride-sharing/e-bike startup.

What this covers

Two open-ended analyses; the system and scenario in each were chosen independently within the module's assessment framework, not fixed by the brief.

1. Human-error analysis of a messaging app

Applied HEHAZOP (systematic guideword-based hazard and operability analysis) and HEART (Human Error Assessment and Reduction Technique) to the task of sending a message to a group chat, identifying three realistic failure modes and their real-world consequences:

Selecting the wrong group chat (a slip, action-based) — with a direct GDPR Article 5 data-disclosure consequence if sensitive information reaches the wrong recipients
Incomplete message composition due to interruption (a lapse, memory-based)
Premature send before proofreading is complete (a skill-based slip — the send action is so over-practised it runs without conscious intention)

Critically evaluated HEART's own output: the calculated Human Error Probability came to 12.4 — mathematically impossible, since probabilities cannot exceed 1.0. Explained why: HEART's generic task types and NHEP values were calibrated against industrial and safety-critical domains (nuclear power, aviation), and multiplicative Performance Shaping Factors compound rapidly when several apply at once — a known limitation of the technique outside the context it was built for. Proposed CREAM (Cognitive Reliability and Error Analysis Method) as a better-fitted alternative for consumer interaction contexts.

2. AI-generated risk assessment critique (ride-sharing case study)

Used Google Gemini to generate ethical, safety, and security/privacy risk reports for a fictional ride-sharing and e-bike startup, then:

Iteratively refined the prompts across six versions, tracking and justifying each refinement (e.g. adding an explicit STRIDE-mapping and rationale requirement transformed a plain ranked list into a structured, defensible one)
Critically evaluated the AI's output against UK regulatory frameworks — UK GDPR, Equality Act 2010, PCI DSS v4.0, Working Time Regulations 1998, Health and Safety at Work Act 1974 — and established risk methodologies (STRIDE, ISO 31000, ALARP)
Identified a specific reasoning failure in the AI's output: it ranked a low-likelihood/high-severity emergency-communication-failure risk as lowest priority on probability grounds alone — the wrong approach for catastrophic-hazard safety cases, per Leveson's systems-safety theory, which requires such hazards to be addressed regardless of assessed likelihood
Proposed three additional, legally-grounded mitigations the AI's output had missed: independent third-party safety auditing, mandatory cybersecurity awareness training for staff, and a documented data minimisation and retention policy
Concluded that GenAI is useful for rapid, broad initial risk identification, but is not a substitute for expert analysis — it consistently under-specified operational detail, omitted UK-specific legal context unless explicitly prompted for it, and every AI-generated claim required independent verification against primary sources before use
Why this is relevant beyond the module

The thread running through both analyses is the same: not accepting an automated or AI-generated verdict at face value, and being precise about where and why it fails when checked against the real regulatory or methodological framework. That is directly the instinct IGA and security-governance work depends on — an access certification, a control attestation, or an AI-assisted risk score is only as trustworthy as the verification behind it.

Frameworks and standards applied

HEHAZOP · HEART · Reason's Skill-Rule-Knowledge model · STRIDE threat modelling · ISO 31000 · ALARP · UK GDPR · Equality Act 2010 · PCI DSS v4.0 · Working Time Regulations 1998 · Health and Safety at Work Act 1974

Full submission

The complete assessed submission (24 pages — full HEHAZOP/HEART tables, the AI prompt log with refinement notes, and reference list) is included as report.pdf.
