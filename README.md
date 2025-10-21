# 📊 Statistics Project

## 🧾 Description
This project covers fundamental and advanced topics in **statistical analysis** — including **PDF, PMF, CDF**, and various **hypothesis testing methods** such as t-test, z-test, ANOVA, Chi-square, and F-test.  
The goal of this project is to perform statistical inference and hypothesis testing on data using Python.

---

## 📚 Topics Covered

### 1️⃣ Probability Distributions
- **PMF (Probability Mass Function)** – Defines probabilities for discrete random variables.  
- **PDF (Probability Density Function)** – Defines probability density for continuous random variables.  
- **CDF (Cumulative Distribution Function)** – Represents the cumulative probability up to a certain value.

---

### 2️⃣ Hypothesis Testing
A method to make inferences about populations using sample data.  

**Steps:**
1. Define null hypothesis (H₀) and alternative hypothesis (H₁)  
2. Choose significance level (α)  
3. Calculate the test statistic  
4. Compute the p-value  
5. Make a decision (Reject or Fail to Reject H₀)

---

### 3️⃣ Confidence Interval (CI)
A range of values likely to contain the population parameter.  

**Formula (for mean):**
\[
CI = \bar{X} \pm Z_{\alpha/2} \left(\frac{\sigma}{\sqrt{n}}\right)
\]

**Example:**  
“The population mean is estimated to lie between 48.2 and 52.6 with 95% confidence.”

---

### 4️⃣ t-Test
Used when the **population standard deviation is unknown**.  

**Types:**
- One-sample t-test  
- Independent two-sample t-test  
- Paired t-test  

**Use case:** Compare means of two small samples.

---

### 5️⃣ z-Test
Used when the **population standard deviation is known** and **sample size > 30**.  

**Applications:**
- Test for population mean  
- Test for population proportion  

**Example:** Test if a coin is fair or biased.

---

### 6️⃣ ANOVA (Analysis of Variance)
Used to compare means across **three or more groups**.  

- **Null hypothesis (H₀):** All group means are equal  
- **Alternative hypothesis (H₁):** At least one group mean is different  
- **Outputs:** F-statistic and p-value

---

### 7️⃣ Chi-Square Test (χ²)
Used for **categorical data** to test relationships or distribution fit.  

**Types:**
- Chi-square Goodness of Fit Test  
- Chi-square Test of Independence  

**Example:** Check if gender and product preference are independent.

---

### 8️⃣ F-Test
Used to compare **two population variances**.  

**Formula:**
\[
F = \frac{s_1^2}{s_2^2}
\]

Commonly used as part of ANOVA.

---

## ⚙️ Tools & Libraries
- Python  
- NumPy  
- Pandas  
- SciPy  
- Matplotlib / Seaborn  

---

## 🧠 How to Run
```bash
# Step 1: Clone the repository
git clone <your_repo_link>

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Run the notebook or Python file
python main.py
