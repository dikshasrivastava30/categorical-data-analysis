# 📊 Categorical Probability Distributions & Data Analysis

## 📁 Overview

This project focuses on applying statistical concepts of **Binomial** and **Poisson distributions** using real-world-inspired and simulated data. It includes three key tasks:

---

## 🔍 Task 1 – Real-Life Scenario (Qualitative & Quantitative Features)

**Scenario**: Customer Visits at a Coffee Shop

### Qualitative (Categorical) Attributes:
- Beverage Type (e.g., Coffee, Tea, Smoothie)
- Payment Method (e.g., Cash, Card, Mobile Wallet)
- Time of Visit (e.g., Morning, Afternoon, Evening)

These are categorical variables that represent groupings without numeric meaning.

### Quantitative (Numerical) Attributes:
- Number of Customers per Hour – Discrete
- Waiting Time (in minutes) – Continuous
- Total Bill Amount per Customer (in ₹) – Continuous

These are measurable quantities. Discrete values are countable (like customers), while continuous ones can take any value in a range (like time or money).

---

## ✅ Task 2 – Binomial & Poisson Applications

### Binomial Distribution:
- Scenario: Estimating how many customers out of 100 choose coffee during three weekly visits.
- Outcome: The data fit a Binomial distribution well with an estimated probability of ordering coffee around 35%.
- Statistical inference confirmed the model was appropriate using a chi-square goodness-of-fit test.

### Poisson Distribution:
- Scenario: Modeling the number of customer arrivals per minute.
- Outcome: The average number of arrivals per minute was about 4.
- The data matched the Poisson distribution well, as verified by chi-square test and model fit evaluation.

---

## 📌 Task 3 – Fitting a Poisson Model in R

- Simulated data of customer arrivals per minute was used to fit a Poisson model.
- The average rate (λ) was estimated and compared with expected frequencies.
- The goodness-of-fit test supported that the observed data aligned with the Poisson assumption.

---

## 📚 References

- Simulated data using statistical assumptions
- Standard concepts from Casella & Berger – *Statistical Inference*
- General Poisson/Binomial theory from R documentation and course materials

---

## 🛠 Tools Used

- R programming language
- Data visualization using base R graphics
- Statistical inference methods (MLE, Chi-Square Test)

---

## ✉️ Contact

For questions or collaboration, feel free to reach out via GitHub Issues.

---

⭐ If you found this useful, consider starring the repository!

