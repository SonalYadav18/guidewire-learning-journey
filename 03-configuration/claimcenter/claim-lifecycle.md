# 🔁 Claim Lifecycle – Setup Claim (Post-FNOL Activities)

Once the **First Notice of Loss (FNOL)** is submitted, ClaimCenter begins the **"Setup Claim"** phase. This includes various follow-up activities needed to prepare the claim for handling and resolution.

---

## 🧩 What Happens After FNOL?

The claim enters the **"Post-FNOL" stage**, where the following tasks are triggered:

### 🔹 1. Claim Segmentation
- The claim is **classified** based on complexity, severity, and other business rules.
- This determines:
  - The **workplan** to be followed
  - Which **adjuster or team** should handle the claim
  - Whether the claim needs **escalation**

> 🔍 Example: A simple glass damage claim may be routed for fast-track processing. A complex injury claim may be routed to a senior adjuster.

---

### 🔹 2. Workplan Creation
- Based on segmentation, a **custom workplan** is generated.
- Workplan = list of tasks (called **activities**) assigned to users

Typical activities might include:
- Review claim details
- Request documents
- Contact insured/third party
- Set up exposures and reserves

---

### 🔹 3. Update FNOL Details
- FNOL data may be incomplete or need refinement
- Adjuster updates:
  - Loss details
  - Party information (claimant, witnesses)
  - Damage description
  - Attachments or photos

---

## ✅ Summary

| Step | Description |
|------|-------------|
| Segmentation | Classify the claim for routing |
| Workplan | Auto-generate activities based on rules |
| Data Refinement | Adjusters update and verify FNOL data |

---

> 🧠 This phase prepares the claim to be **actively worked on**, setting the stage for exposures, payments, and closure.

# 🔁 Claim Lifecycle – Post-FNOL to Closure

This document explains the full sequence of claim processing activities in ClaimCenter after the FNOL (First Notice of Loss) is submitted.

---

## 🧱 1. Create Exposures

### 📌 What is an Exposure?
An **Exposure** is an event that may result in a **payment or liability**. It tracks potential claim payouts.

### 📍 Key Concepts:
- Linked to a **Coverage** (source of funds)
- Linked to a **Claimant** (receiver of funds)
- Can be **auto-created** based on rules or added manually by an adjuster
- One claim can have **multiple exposures** depending on the incident type

> 🧠 Example: A car accident may have exposures for bodily injury, property damage, and towing.

---

## 💰 2. Create Reserves

### 📌 What is a Reserve?
A **Reserve** is the estimated amount of money set aside to **settle a claim**.

### 📍 Key Points:
- Can be auto-calculated using business rules
- Can also be manually set by the adjuster
- Serves as a financial placeholder for expected payouts

> Reserves ensure the company is financially prepared to settle claims accurately.

---

## 💸 3. Claim Costs vs. Expenses

Claim payments are split into two categories:

| Type | Description |
|------|-------------|
| **Claim Cost** | Amount paid directly to the claimant (e.g., medical bills, repairs) |
| **Claim Expense** | Operational costs (e.g., legal fees, investigation services) |

ClaimCenter tracks both separately for reporting and accounting purposes.

---

## ✅ 4. Complete Activities

### 📌 Activities
- Tasks assigned to users (adjusters, supervisors)
- Can be auto-generated by ClaimCenter rules or manually added

Examples:
- Contact insured
- Review photos
- Schedule inspection
- Approve payment

---

## 💵 5. Make Claim Payable

Once all required activities and investigations are complete:
- Claim is marked **payable**
- This allows check issuance or electronic payments to begin

---

## 🧾 6. Issue Checks

Adjuster or system initiates payment to:
- Claimants
- Vendors (repair shops, doctors, etc.)
- Legal services

Payments are processed as:
- One-time checks
- Scheduled payments
- Split between multiple payees if needed

---

## 🚫 7. Close the Claim

A claim can be closed only when:
- ✅ All exposures are **closed**
- ✅ All activities are **completed**
- ✅ All services are resolved
- ✅ **Fault rating** is determined (if applicable)

Claim closure signals that no further processing or payments are expected.

---

## 🧠 Summary: End-to-End Flow

1. **Setup claim** (after FNOL)
2. **Segment** and assign workplan
3. **Create exposures** (auto/manual)
4. **Set reserves**
5. **Complete activities**
6. **Mark claim as payable**
7. **Issue checks**
8. **Close claim** when all parts are completed.


### What is an Exposure?

🔹 Definition:
An Exposure in ClaimCenter is a specific part of a claim that represents a potential payment or liability.

Think of a claim as a folder, and exposures as the individual line items inside it that money may be paid for.



### What is Fault Rating?

🔍 Definition:
Fault Rating refers to how responsible each party is for causing the incident or loss.

It’s typically a percentage assigned to each party involved in the claim.

🔁 Why It Matters:
It affects liability and subrogation.
Helps determine how much the insurer will pay vs. try to recover from others.
Can influence premiums and legal handling.

