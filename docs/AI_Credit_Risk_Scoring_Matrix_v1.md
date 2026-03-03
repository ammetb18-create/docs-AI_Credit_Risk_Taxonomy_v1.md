# AI Credit Risk Scoring Matrix v1

## Purpose
This matrix provides a structured method to assess and score AI-related risk in automated credit decision systems. It converts the project's risk taxonomy into measurable, repeatable evaluation criteria for governance, compliance, and monitoring.

---

## Scoring Scale (1–5)
- **1 (Low):** Minimal risk, strong controls, low impact
- **2 (Moderate):** Some risk, partial controls, limited impact
- **3 (High):** Clear risk, weak controls, meaningful impact
- **4 (Very High):** Significant risk, gaps likely to cause harm or non-compliance
- **5 (Critical):** Severe risk, high likelihood of harm or regulatory exposure

---

## Risk Dimensions & Indicators

### 1) Algorithmic Bias Risk
**Indicators**
- Disparate impact signals in outcomes (approval/denial rate differences)
- Proxy variable exposure (ZIP code, employment gaps, etc.)
- Historical bias amplification through training data

**Controls to check**
- Fairness testing in development and monitoring
- Documented mitigation plan (threshold adjustments, feature review)
- Periodic re-evaluation of proxy variables

**Score (1–5):** ___

---

### 2) Regulatory Compliance Risk (ECOA / Fair Lending / Documentation)
**Indicators**
- Weak adverse action reasoning/explanations
- Missing documentation of model intent, limits, and validation
- Inability to justify decision logic under audit

**Controls to check**
- Audit-ready documentation set (model cards / decision logs)
- Review cycles and compliance sign-off
- Clear accountability owner for compliance

**Score (1–5):** ___

---

### 3) Model Transparency Risk
**Indicators**
- Black-box scoring dependency without explainability layer
- Low interpretability of key drivers
- Lack of traceable decision record

**Controls to check**
- Explainability artifacts (reason codes, feature importance summaries)
- Decision traceability (logs, versioning, change control)
- Human review escalation triggers

**Score (1–5):** ___

---

### 4) Operational Risk
**Indicators**
- Model drift not monitored
- Data pipeline integrity issues
- Governance oversight gaps (no owner, no cadence)

**Controls to check**
- Drift monitoring plan + alert thresholds
- Data quality checks and incident response process
- Defined governance roles and review cadence

**Score (1–5):** ___

---

### 5) Reputational & Systemic Risk
**Indicators**
- Consumer trust erosion signals (complaints, public scrutiny)
- Litigation exposure
- Institutional instability (regulatory consent orders, repeated failures)

**Controls to check**
- Escalation and remediation plan
- Stakeholder communication plan
- Independent review capability

**Score (1–5):** ___

---

## Total Risk Score
Add the five dimension scores:

**Total (5–25):** ___

### Risk Tier (based on total)
- **5–9:** Low
- **10–14:** Moderate
- **15–19:** High
- **20–25:** Critical

**Tier:** ___

---

## Notes
- This scoring is designed to be repeatable across systems and institutions.
- Scores should be justified with brief evidence notes during evaluation.
