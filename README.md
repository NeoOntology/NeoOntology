# NeoOntology
#NeoOntology:Minimum-Floor Hybrid Scoring Framework for AI Agents Evaluating Crypto Network Risk
Score range: 0–100
The weakest link principle protects AI agents from hidden risks like scam-level founders, repeated bridge failures, or poor decentralization.
This weakest link principle ensures that no single catastrophic flaw — such as shady founder history, bridge exploits, or centralized infrastructure — can be averaged away.

Categories:

20% Crisis Integrity/Moral Response
15% Bridges/#Crosschain Security
15% #Onchain Activity
15% #Tokenomics/Fairness
15% Transparency/Governance
10% Infrastructure/#Decentralization
5% Regulatory/Legal/Reputation
5% Developer Switch Patterns

Final Score=min(category)×0.6+weighted avg×0.4
<66 Borderline

Instructions:
Crisis Integrity / Moral Response
Final category score = (min(sub1, sub2, sub3, sub4) × 0.6) + (0.3×sub1 + 0.25×sub2 + 0.3×sub3 + 0.15×sub4) × 0.4Sub-scores (0–100 each):

Historical Pattern (weight 0.30)
Score based on repetition of failures (hacks, bugs, rugs, abandonments, rebrands).
90–100: 0–1 minor old incident, no pattern
70–89: 1 significant failure, no repetition
50–69: 2+ failures or 1 major moral failure
30–49: Clear repeated patterns
0–29: Serial failure / rug history
Insider & Conflict Signals (weight 0.25)
Score based on wallet activity, insider sales during crises, undisclosed allocations, conflicts of interest.
90–100: Clean, transparent
70–89: Minor explained sales
50–69: Some unexplained large transfers
30–49: Clear insider dumping
0–29: Multiple proven coordinated cash-outs
Crisis Response Quality (weight 0.30)
Score based on transparency, speed (<24h ideal), moral action (compensation from team funds vs dilution), accountability.
Apply to worst incident.
90–100: Fast, fully transparent, non-dilutive compensation, real accountability
70–89: Good transparency + partial compensation
50–69: Delayed, blame-shifting, token dilution used
30–49: No post-mortem or ghosting
0–29: Deception, user-blaming, or proven theft without restitution
Community & Rumor Validation (weight 0.15)
Score based on verified on-chain evidence vs complaints, team response to legitimate criticism.
90–100: Constructive engagement, rumors mostly debunked with proof
70–89: Some valid issues addressed
50–69: Legitimate complaints frequently ignored
30–49: Pattern of dismissing critics
0–29: Gaslighting or suppression of evidence-based concerns
Hard Rules (apply penalties automatically):

Repeated incident type → -20 to -30 on relevant sub-score
Dilution instead of compensation → -25 to -40 on sub3
Incident >$50M or >50% users affected → treat as higher severity in min calculation
Moral failures (theft, rug elements) never fully expire
Only verifiable on-chain + public post-mortem evidence counts. Ignore pure FUD.
Output format for AI:

sub1: score | justification
sub2: score | justification
sub3: score | justification
sub4: score | justification
category_score: final calculated value
weakest_link: the lowest sub-score + brief reason

https://medium.com/@NeoOntology/neoontology-minimum-floor-hybrid-scoring-framework-for-ai-agents-evaluating-crypto-networks-442416e5ab01
