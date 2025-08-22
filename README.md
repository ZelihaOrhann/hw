# **Final Project**

Exercise 2 
## **START**

Exercise 3 

This notebook has been prepared to list fundamental concepts in the context of data science, summarize the tools, and demonstrate arithmetic operations with simple Python examples. It also includes a small application example, such as converting minutes to hours.
## **Data Science Languages**

Exercise 4

- Python
- R
- SQL
- Julia
- Scala
- Java
- MATLAB
- JavaScript 
- C/C++ 
## **Data Science Libraries**

Exercise 5

**Python**
- NumPy, pandas, matplotlib, seaborn
- scikit-learn, XGBoost, LightGBM
- TensorFlow, Keras, PyTorch
- statsmodels

**R**
- tidyverse (dplyr, tidyr, readr), ggplot2
- caret, randomForest

**Julia**
- DataFrames.jl, Flux.jl

## **Data Science Tools**

Exercise 6

| Category | Tool | Goal |
|---|---|---|
| Notebook | Jupyter Notebook/Lab | Exploratory Analysis, Experimental Research |
| IDE | VS Code | Coding, debugging, plugins|
| Statistics | RStudio | Data analysis and visualization with R |
| Big Data | Apache Spark | Distributed data processing |
| Virtualization | Tableau / Power BI | Interactive dashboards |
| Business Flow | Apache Airflow | Data pipeline scheduling/orchestration |
| Version Control | Git & GitHub | Code versioning and collaboration |
| Deployment | Docker | Application packaging and portability |

## **Introduction to Arithmetic Expression Examples**

Exercise 7

Arithmetic expressions include operations such as addition (+), subtraction (-), multiplication (*), division (/), exponentiation (**), and modulo (%). Examples:

- $2 + 3 = 5$
- $4 \times 5 = 20$
- $10 / 3 \approx 3.33$
- $2^3 = 8$
- $16$'nın karekökü $\sqrt{16} = 4$

# Exercise 8
a = 6
b = 7

carpim = a * b
toplam = a + b

print(f"a = {a}, b = {b}")
print(f"Result (a*b) = {carpim}")
print(f"Result (a+b) = {toplam}")
# Exercise 9
def dakika_to_saat(dakika: int):
    """Converts minutes into hour:minute format and decimal hours."""
    if dakika < 0:
        raise ValueError("Minute is not negative")
    saat = dakika // 60
    kalan_dakika = dakika % 60
    ondalik_saat = dakika / 60
    return saat, kalan_dakika, ondalik_saat

# Örnek kullanım
ornekler = [90, 135, 160, 250]
for d in ornekler:
    s, k, o = dakika_to_saat(d)
    print(f"{d} minute = {s} hour {k} minute (≈ {o:.2f} hour)")
## **Goals**

Exercise 10

- Identify the languages and libraries in the data science ecosystem

- Learn the basic tools and their applications

- Apply arithmetic using simple Python expressions

- Develop a small real-world function (minutes → hours)

- Document the workflow by sharing the notebook on GitHub
## **Author**

Exercise 11

**Zeliha Orhan**
