# 🚗 Cars24 Used Car Price Predictor

An interactive end-to-end Machine Learning web application that estimates the resale value of used cars based on historical Cars24 marketplace data.

---

## 📌 Project Overview
Buying or selling a pre-owned vehicle requires a clear understanding of fair market valuation. This application uses regression modeling to predict used car prices by evaluating key vehicle specifications, including fuel type, transmission type, engine capacity, and seating capacity.

- **Predicted Output Unit:** Price in **Lakhs (INR ₹)**
- **Target Marketplace:** Indian Pre-Owned Car Market (Cars24 Data)

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, OpenPyXL
- **Web Framework:** Streamlit
- **Deployment:** Streamlit Community Cloud

---

## ⚙️ How It Works
1. **User Input:** Select vehicle attributes via interactive sliders and dropdowns (Fuel Type, Engine CC, Transmission, Seating Capacity).
2. **Feature Preprocessing:** Categorical features are mapped into model-compatible numerical encodings.
3. **Inference:** A pre-trained regression pipeline loaded via `pickle` generates the valuation.
4. **Result:** The predicted estimated value is displayed instantly on screen.

---
## 🚀 Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/sanasheikh01206-bot/Cars24-used-price-prediction.git](https://github.com/sanasheikh01206-bot/Cars24-used-price-prediction.git)
   cd Cars24-used-price-prediction


