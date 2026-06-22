# 🛍️ Smart Product Recommendation Engine

An AI-powered recommendation system that suggests **complementary fashion products** instead of merely showing visually similar items. This project was developed as part of the **Gen AI Bootcamp Day 2 Homework Challenge**.

---

## 📌 Problem Statement

Traditional product search systems typically return products that look similar to the selected item.

For example:

**Input Product:**

* Running Shoe

**Traditional Output:**

* Running Shoe A
* Running Shoe B
* Running Shoe C

However, modern e-commerce platforms recommend products that are commonly purchased together.

**Desired Output:**

* Sports Socks
* Fitness Watch
* Track Pants

This project implements a recommendation engine capable of suggesting complementary products to improve user experience and cross-selling opportunities.

---

## 🎯 Objectives

* Build a smart recommendation engine for fashion products.
* Suggest complementary products instead of similar products.
* Visualize recommendations using product images.
* Explain recommendation logic.
* Demonstrate practical AI-powered e-commerce applications.

---

## 📂 Dataset

Fashion Product Images Dataset from Kaggle:

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

Dataset contains:

* Product Images
* Product Categories
* Product Metadata
* Product Descriptions

---

## 🏗️ Project Architecture

```text
Input Product
      │
      ▼
Identify Product Category
      │
      ▼
Recommendation Rule Engine
      │
      ▼
Find Complementary Categories
      │
      ▼
Retrieve Matching Products
      │
      ▼
Display Recommendations
```

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Pillow (PIL)
* Jupyter Notebook / Kaggle Notebook

---

## 📁 Project Structure

```text
Smart-Product-Recommendation/

│
├── notebook.ipynb
├── README.md
├── report.pdf
├── images/
└── screenshots/
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/smart-product-recommendation.git

cd smart-product-recommendation
```

Install required packages:

```bash
pip install pandas numpy matplotlib pillow
```

---

## 📊 Recommendation Logic

The recommendation engine uses a predefined knowledge base of complementary products.

Example:

```python
recommendation_rules = {

    "Shoes": [
        "Socks",
        "Watches",
        "Track Pants"
    ],

    "Shirts": [
        "Jeans",
        "Belts",
        "Watches"
    ],

    "Jeans": [
        "Tshirts",
        "Shoes",
        "Belts"
    ]
}
```

When a product is selected:

1. Product category is identified.
2. Related categories are retrieved.
3. Products from those categories are recommended.
4. Results are visualized.

---

## 📷 Example Output

### Input Product

Nike Running Shoe

### Recommended Products

* Sports Socks
* Fitness Watch
* Track Pants

---

## 📈 Visualization

The notebook displays recommended products along with their images using Matplotlib.

Example:

```python
show_recommendations(product_id)
```

This generates a visual recommendation gallery for the selected product.

---

## 🔍 Future Enhancements

* CLIP-based Image Embeddings
* Vector Search using FAISS
* User Personalization
* Purchase History Analysis
* Deep Learning Recommendation Models
* Real-Time API Deployment

---

## 📊 Results

The recommendation engine successfully:

✅ Identifies product categories

✅ Generates complementary product recommendations

✅ Visualizes recommendations

✅ Demonstrates cross-selling capability

✅ Provides explainable recommendation logic

---

## 🎓 Gen AI Bootcamp Challenge

This project was developed for the **Gen AI Bootcamp Day 2 Homework Challenge – AI Product Intelligence System**.

Task Implemented:

✔ Task 1 – Smart Product Recommendation Engine

---

## 👩‍💻 Author

**Ann Titta**

Engineer | AI Enthusiast | Python Developer

GitHub: https://github.com/your-github-username

---

## 📜 License

This project is intended for educational and research purposes.
