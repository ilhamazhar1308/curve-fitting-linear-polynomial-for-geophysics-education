# curve-fitting-linear-polynomial-for-geophysics-education
This project demonstrates the application of curve fitting techniques using Linear Regression and Polynomial Regression to analyze the relationship between two physical variables, such as depth and temperature, which are commonly encountered in geophysical and geothermal studies.

---

## Objectives
The objectives of this program are:
- To introduce the basic concept of curve fitting
- To understand linear and polynomial regression models
- To visualize geophysical data trends
- To support learning in geophysics and scientific programming

---

## What is Curve Fitting?
Curve fitting is a mathematical technique used to find a function that best represents a set of observed data points.

In geophysics, curve fitting is used to:
- Identify subsurface trends
- Approximate physical relationships
- Support interpretation of temperature, gravity, magnetic, and resistivity data

---

## 🔹 Method 1: Linear Regression

### Concept
Linear regression assumes a linear relationship between variables:

T = aZ + b

Where:
- T = temperature  
- Z = depth  
- a = slope (gradient)  
- b = intercept  

### Geophysical Interpretation
- The slope represents the temperature gradient
- Commonly used in geothermal gradient estimation
- Suitable for simple and shallow subsurface models

---

### Step-by-Step Code Explanation (Linear Regression)
1. Import numerical and plotting libraries  
2. Input depth and temperature data  
3. Compute summation terms (Σx, Σy, Σx², Σxy)  
4. Calculate slope and intercept using least squares method  
5. Generate linear fitted values  
6. Plot original data and fitted line  

---

## 🔹 Method 2: Polynomial Regression

### Concept
Polynomial regression models non-linear relationships using higher-degree equations:

y = aₙxⁿ + aₙ₋₁xⁿ⁻¹ + ... + a₁x + a₀

###  Geophysical Interpretation
- Suitable for complex geothermal systems
- Captures variable thermal gradients
- Represents layered or convective subsurface conditions

---

### Step-by-Step Code Explanation (Polynomial Regression)
1. Input depth and temperature data  
2. Define polynomial degree  
3. Compute polynomial coefficients using least squares  
4. Construct polynomial function  
5. Generate smooth fitted curve  
6. Plot original data and polynomial curve  

---

## Comparison of Methods

| Aspect | Linear Regression | Polynomial Regression |
|------|------------------|----------------------|
| Model Type | Linear | Non-linear |
| Complexity | Low | Higher |
| Interpretation | Simple | More detailed |
| Risk | Oversimplification | Overfitting |
| Educational Value | Fundamental | Advanced |

---

## Curve Fitting in Geophysics
Curve fitting is widely used in geophysics for:
- Temperature–depth analysis  
- Gravity anomaly trend estimation  
- Magnetic data interpretation  
- Resistivity sounding curve analysis  

This project introduces these concepts in a simplified and controlled educational framework.

---

## ⚠️ Educational Disclaimer
This program is intended **strictly for educational and academic purposes only**.

- Not suitable for professional exploration or decision-making  
- Real geophysical interpretation requires multidisciplinary validation  

---

## Target Users
- Geophysics students  
- Earth science students  
- Beginners in Python data analysis  
- Academic learning and practice  

---

## Tools Used
- Python  
- NumPy  
- Matplotlib  

---

## Author
**Ilham Azhar**  
Geophysical Engineering  
Sumatera Institute of Technology (ITERA)

---

## Conclusion
This project provides a fundamental understanding of curve fitting using linear and polynomial regression, supporting both mathematical comprehension and basic geophysical interpretation skills in an educational context.
