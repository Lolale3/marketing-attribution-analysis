# Multi-Touch Marketing Attribution Analysis (GA4)

This project analyzes customer journeys using event-level Google Analytics 4 (GA4) data to understand how different marketing channels contribute to conversions.

The goal is to move beyond traditional last-click attribution and evaluate channel performance across the full customer journey.

---

## 🚀 Business Problem

Customers interact with multiple marketing channels before converting, but most analytics systems rely on last-click attribution, which assigns full credit to the final interaction.

This can misrepresent the contribution of earlier touchpoints such as acquisition and engagement channels.

This project addresses:

- Which channels drive customer acquisition?
- Which channels close conversions?
- Which channels assist throughout the journey?
- How attribution models change marketing insights

---

## 📊 Approach

The analysis follows a structured workflow:

1. Data extraction from GA4 event dataset  
2. Data cleaning and channel grouping  
3. Customer journey reconstruction  
4. Attribution modeling:
   - First-click attribution  
   - Last-click attribution  
   - Linear attribution  
5. Assisted conversion analysis  
6. Channel performance evaluation  

---

## 🔍 Key Insights

- Organic Search drives the highest traffic and plays a key role in customer acquisition  
- Referral channels significantly assist conversions in mid-funnel stages  
- Direct traffic dominates final conversion touchpoints, indicating returning users  
- Linear attribution highlights the multi-touch nature of customer journeys  
- Last-click attribution underestimates the contribution of early-stage channels  

---

## 📈 Why This Matters

The analysis demonstrates that relying solely on last-click attribution can lead to suboptimal marketing decisions.

A multi-touch attribution approach provides a more accurate understanding of channel performance and supports better budget allocation.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Google Analytics 4 dataset (BigQuery)
- Matplotlib for visualization

---

## 📁 Project Structure
