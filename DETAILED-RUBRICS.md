# #NeoOntology Detailed Rubrics

This file contains the full sub-score rubrics for every category in the #NeoOntology Minimum-Floor Hybrid Scoring Framework.

Each category applies the same hybrid logic:  
**Category Score = (Min Sub-score × 0.6) + (Weighted Average of Sub-scores × 0.4)**

Hard Rules apply across all categories:
- Repeated incidents of the same type → automatic -20 to -40 penalty on relevant sub-score(s)
- Large incidents (> $50M loss or >50% users affected) → treat as higher severity
- Moral failures, deception, or theft without restitution → never fully expire
- Only verifiable evidence (on-chain data, official post-mortems, public statements) counts. Pure FUD is ignored.

---

## 1. Crisis Integrity & Moral Response (20%)

**Final category score = (min(sub1, sub2, sub3, sub4) × 0.6) + (0.30×sub1 + 0.25×sub2 + 0.30×sub3 + 0.15×sub4) × 0.4**

**Sub-scores (0–100):**

- **Historical Pattern of Failures** (weight 0.30)  
  90–100: No meaningful incidents or only 1 minor old issue with no pattern  
  70–89: 1 significant failure, properly resolved, no repetition  
  50–69: 2+ failures or 1 major moral failure  
  30–49: Clear repeated patterns of failure  
  0–29: Serial failures, rugs, or history of abandonment/rebrands to escape accountability

- **Insider & Conflict Signals** (weight 0.25)  
  90–100: Clean history, high transparency, no suspicious activity  
  70–89: Minor, well-explained insider sales or transfers  
  50–69: Unexplained large transfers or potential conflicts of interest  
  30–49: Clear insider dumping during crises or undisclosed allocations  
  0–29: Multiple proven coordinated cash-outs or severe founder conflicts

- **Crisis Response Quality** (weight 0.30)  
  (Evaluate the worst major incident)  
  90–100: Extremely fast (<24h), fully transparent, non-dilutive compensation from team/foundation funds, genuine accountability + post-mortem  
  70–89: Good transparency and partial compensation  
  50–69: Delayed response, blame-shifting, or use of token dilution  
  30–49: No post-mortem, ghosting users, or minimal engagement  
  0–29: Deception, user-blaming, proven theft without restitution, or gaslighting

- **Community & Rumor Validation** (weight 0.15)  
  90–100: Constructive engagement with critics, most rumors debunked with clear evidence  
  70–89: Some legitimate issues addressed  
  50–69: Legitimate complaints frequently ignored  
  30–49: Pattern of dismissing or attacking critics  
  0–29: Active gaslighting or suppression of evidence-based concerns

**Output for this category (when deep analysis is needed):**  
sub1: score | justification  
sub2: score | justification  
sub3: score | justification  
sub4: score | justification  
category_score: final calculated value  
weakest_link: [lowest sub-score + brief reason]

---

## 2. Bridges & Crosschain Security (15%)

**Sub-scores:**
- Bridge Architecture & Audit Quality (0.35)
- Historical Bridge Incident Record (0.35)
- Dependency Concentration & Single Points of Failure (0.20)
- Response & Recovery Capability (0.10)

**Scoring examples (general guidance):**
- 90–100: Multiple independent audits, no major incidents, diversified bridges, excellent recovery history
- 50–69: Some incidents or heavy reliance on one bridge provider
- 0–29: Repeated exploits, un-audited contracts, or permanent loss of user funds without compensation

---

## 3. Onchain Activity & Ecosystem Health (15%)

**Sub-scores:**
- Genuine Usage & TVL Sustainability (0.40)
- Developer Activity & Code Contributions (0.30)
- User Retention & Growth Trend (0.20)
- Ecosystem Diversity (0.10)

**Scoring examples:**
- High scores require real organic activity, not inflated by incentives or wash trading.
- Heavy penalties for dramatic TVL drops after incentives end or after security incidents.

---

## 4. Tokenomics & Fairness (15%)

**Sub-scores:**
- Initial Distribution & Allocation Fairness (0.30)
- Supply Dynamics & Inflation/Deflation Mechanism (0.25)
- Utility vs Speculation Balance (0.25)
- Vesting Schedules & Team/Investor Lockups (0.20)

**Scoring examples:**
- Strong scores for transparent launches, long vesting, strong utility, and mechanisms that align long-term incentives.
- Heavy penalties for massive unlocked team allocations, hyper-inflation, or "team-controlled" treasuries without oversight.

---

## 5. Transparency & Governance (15%)

**Sub-scores:**
- Public Communication & Financial Reporting (0.35)
- On-chain Governance Quality & Participation (0.30)
- Team/Founder Doxxing & Accountability (0.20)
- Responsiveness to Community Proposals (0.15)

**Scoring examples:**
- Excellent scores require regular audited reports, active on-chain voting with real impact, and identifiable core contributors.

---

## 6. Infrastructure & Decentralization (10%)

**Sub-scores:**
- Node Operator Distribution & Consensus Security (0.40)
- Technical Robustness & Upgrade History (0.30)
- Reliance on Centralized Components (0.20)
- Validator Accessibility & Diversity (0.10)

**Scoring examples:**
- dBFT, heavily permissioned, or founder-controlled validators = lower scores.
- Pure PoS/PoW with wide geographic and entity distribution = higher scores.

---

## 7. Regulatory, Legal & Reputation Risk (5%)

**Sub-scores:**
- Regulatory Exposure & Compliance Efforts (0.40)
- Past Legal Issues or Sanctions (0.30)
- Public Reputation & Media Sentiment (verified only) (0.30)

**Scoring examples:**
- Projects in high-risk jurisdictions with no compliance roadmap or history of regulatory actions score significantly lower.

---

## 8. Developer Switch Patterns & Insider Signals (5%)

**Sub-scores:**
- Core Developer Retention & Activity (0.40)
- Sudden Team/Contributor Exits During Crises (0.30)
- Public Conflicts or "Rug Signals" from Insiders (0.30)

This category often overlaps with Crisis Integrity and Insider Signals but focuses specifically on developer behavior patterns over time.

---

**Usage Note for AI Agents:**

When the user requests a standard #NeoOntology assessment, use the high-level category scores with short justifications (as defined in SYSTEM-PROMPT.md).  
Only when deeper analysis is needed (or specifically requested), expand the weakest category using the full sub-score rubrics from this file and show the detailed sub-score output.

Always prioritize the **Weakest Link Rule** — never let strong categories hide fatal flaws.
