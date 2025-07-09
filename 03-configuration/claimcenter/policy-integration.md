# 🔗 ClaimCenter and Policy System Integration

This note explains how and when ClaimCenter communicates with the external **Policy System** (such as PolicyCenter or another source of truth for policy data).

ClaimCenter integrates with the policy system **three times per claim**, typically during the FNOL process and claim handling stages.

---

## 🔁 1. Policy Search

- **When**: During First Notice of Loss (FNOL)
- **What Happens**: CSR or Adjuster searches for the correct policy using:
  - Policy number
  - Name of insured
  - Date of loss
- **Why**: To identify and link the correct policy to the new claim
- **Outcome**: Policy list is displayed to the user for selection

---

## 📥 2. Policy Retrieval

- **When**: After policy is selected during FNOL
- **What Happens**: ClaimCenter pulls full policy details including:
  - Policy term
  - Coverage types and limits
  - Covered parties and assets (vehicles, properties)
- **Why**: To verify whether the reported loss is covered under the selected policy
- **Outcome**: Populates claim fields with policy data

---

## 🔄 3. Policy Refresh

- **When**: After the claim is created (can be triggered manually or automatically)
- **What Happens**: ClaimCenter re-requests updated policy data to reflect:
  - Mid-term endorsements (policy changes)
  - Coverage updates
  - Renewals
- **Why**: To ensure claim decisions are based on the **most current policy version**
- **Outcome**: Keeps claim and policy data in sync

---

## 🧠 Summary Table

| Contact Point     | Triggered When | Purpose                     | System Behavior |
|------------------|----------------|-----------------------------|------------------|
| **Policy Search**   | FNOL start       | Identify matching policy     | List policies |
| **Policy Retrieval**| FNOL after selection | Pull full policy details      | Populate claim |
| **Policy Refresh**  | Post-FNOL / On demand | Update policy changes         | Re-sync policy info |

---

> ✅ ClaimCenter needs accurate policy data to determine **coverage eligibility**, **payment limits**, and **claim routing** — these three points ensure reliable integration with the policy system.

### What is an Endorsement?

An endorsement (also called a rider) is a change or addition to an existing insurance policy. It modifies the coverage, either by:

Adding something new
Removing something
Changing the terms
Think of it as an official amendment to the policy — like editing a legal contract.
