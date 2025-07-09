# 🧠 Claim Segmentation in ClaimCenter

**Segmentation** is the process of classifying a claim based on its **complexity, severity, or risk**, immediately after FNOL (First Notice of Loss). It helps route claims to the right handler and generate a relevant workplan.

---

## 🎯 Purpose of Segmentation

- Assign claims to appropriate users (e.g., adjusters or supervisors)
- Determine workflow complexity (e.g., fast-track vs. full investigation)
- Apply business rules to improve claim handling efficiency
- Reduce handling time for low-risk claims

---

## ⚙️ How Segmentation Works

Segmentation in ClaimCenter is rule-based and often driven by the following:

| Factor              | Example                             |
|---------------------|--------------------------------------|
| Type of Loss         | Auto, Theft, Injury                 |
| Claim Amount         | ₹10,000 vs ₹2,00,000                |
| Number of Exposures  | Single vs. multiple injuries        |
| Line of Business     | Personal vs. Commercial             |
| Prior Claim History  | High frequency = higher risk        |

The segmentation engine assigns the claim to a **segment type**, which influences the rest of the claim flow.

---

## 🧩 Common Segments

| Segment      | Description                            | Action                                 |
|--------------|----------------------------------------|----------------------------------------|
| **Fast Track** | Low complexity, low amount             | Auto-approved or minimal review        |
| **Standard**   | Moderate risk                          | Assigned to standard adjuster          |
| **Complex**    | High-value, multiple exposures         | Routed to senior adjuster              |
| **Fraud Risk** | Pattern of suspicious activity         | Sent to SIU (Special Investigation Unit)|

---

## 🔁 When It Happens

- Immediately after FNOL
- Before or during the **"Setup Claim"** stage
- Can be re-evaluated later if claim details change

---

## 🧠 Summary

| Aspect        | Details |
|---------------|---------|
| What          | Classify claim by risk or complexity |
| When          | After FNOL, during Setup Claim       |
| Why           | Route efficiently, apply correct workflow |
| How           | Driven by business rules and claim attributes |

> ✅ Segmentation enables faster processing of simple claims and better oversight for complex or high-risk cases.

