# Applied Multivariate Analysis
This repository showcases projects completed as part of the STAT 445 course at Simon Fraser University (SFU).  
The projects involve advanced multivariate statistical techniques, including Principal Component Analysis (PCA), correlation analysis, factor analysis, and data visualization using R.

---

## Tools and Libraries
The following tools and libraries were used for the projects:

- **R Programming Language**
- **Libraries**:
  - `tidyverse`
  - `ggplot2`
  - `GGally`
  - `psych`

---

## Projects

### **1. Project 1: Scatterplot Matrix and Correlation Analysis**
- **Objective**: Explore relationships between variables using scatterplot matrices and correlation coefficients.
- **Key Techniques**:
  - Created scatterplot matrices using `GGally::ggpairs()`.
  - Performed correlation analysis to identify relationships between variables.
- **Results**:
  - Identified a strong positive correlation of **0.869** between `AAT` and `AST`.

---

### **2. Project 2: Principal Component Analysis (PCA)**
- **Objective**: Reduce dataset dimensionality and interpret underlying structures.
- **Key Techniques**:
  - Conducted PCA using `prcomp()` in R.
  - Used scree plots and eigenvalue analysis to determine the number of components to retain.
- **Results**:
  - PC1 captured **93.49%** of the total variance, significantly simplifying the dataset.

---

### **3. Project 3: Factor Analysis**
- **Objective**: Identify latent factors that explain relationships among variables and interpret eigenvalues.
- **Key Techniques**:
  - Computed factor loadings and analyzed eigenvalues.
  - Interpreted latent factors to summarize data patterns.
- **Results**:
  - Discovered that fewer factors could sufficiently explain the majority of the dataset's variance.

---

### **4. Project 4: Eigenvalues and Covariance Matrices**
- **Objective**: Investigate covariance structures and eigenvalues for dimensionality reduction.
- **Key Techniques**:
  - Calculated eigenvalues and eigenvectors for PCA.
  - Retained 3 components accounting for over 70% of the total variance.
- **Results**:
  - Provided insights into the most influential variables through eigenvector interpretation.

---

### **5. Project 5: Outlier Detection and Factor Analysis**
- **Objective**: Analyze and adjust for outliers to assess their impact on statistical results.
- **Key Techniques**:
  - Boxplots for outlier detection.
  - Correlation adjustments after removing outliers.
- **Results**:
  - Removing outliers increased the correlation between variables from 0.173 to 0.391, revealing stronger relationships.

---

### **6. Final Project: Comprehensive Multivariate Analysis**
- **Objective**: Combine techniques from previous projects into a comprehensive analysis.
- **Key Techniques**:
  - Integrated PCA, Factor Analysis, and Outlier Detection.
  - Explored variable relationships through correlation matrices and scatterplots.
- **Results**:
  - PCA revealed that PC1 and PC2 explained over **95%** of the total variance.
  - Improved data interpretability by addressing scale and outlier issues.

---

## Resources
All relevant code files, problem statements, and solution reports are organized into the following folders:

### **1. R Scripts**
All R Markdown files for analysis are located in the [`r_code/`](./r_code/) folder:
- [`project1_q1.Rmd`](./r_code/project1_q1.Rmd)
- [`project1_q2.Rmd`](./r_code/project1_q2.Rmd)
- [`project2_q1.Rmd`](./r_code/project2_q1.Rmd)
- [`project2_q2.Rmd`](./r_code/project2_q2.Rmd)
- [`project2_q3.Rmd`](./r_code/project2_q3.Rmd)
- [`project2_q4.Rmd`](./r_code/project2_q4.Rmd)
- [`project2_q5.Rmd`](./r_code/project2_q5.Rmd)
- [`project3_q1.Rmd`](./r_code/project3_q1.Rmd)
- [`project3_q2.Rmd`](./r_code/project3_q2.Rmd)
- [`project3_q3.Rmd`](./r_code/project3_q3.Rmd)
- [`project4_q1.Rmd`](./r_code/project4_q1.Rmd)
- [`project4_q2.Rmd`](./r_code/project4_q2.Rmd)
- [`project4_q3.Rmd`](./r_code/project4_q3.Rmd)
- [`project5.Rmd`](./r_code/project5.Rmd)
- [`Final Project.Rmd`](./r_code/Final%20Project.Rmd)

---

### **2. Problem Statements**
All problem statement files are located in the [`problems/`](./problems/) folder:
- [`project1_problems.pdf`](./problems/project1_problems.pdf)
- [`project2_problems.pdf`](./problems/project2_problems.pdf)
- [`project3_problems.pdf`](./problems/project3_problems.pdf)
- [`project4_problems.pdf`](./problems/project4_problems.pdf)
- [`project5_problems.pdf`](./problems/project5_problems.pdf)
- [`final_project_problems.pdf`](./problems/final_project_problems.pdf)

---

### **3. Solution Reports**
All solution reports are located in the [`solutions/`](./solutions/) folder:
- [`project1_solution.pdf`](./solutions/project1_solutions.pdf)
- [`project2_solution.pdf`](./solutions/project2_solutions.pdf)
- [`project3_solution.pdf`](./solutions/project3_solutions.pdf)
- [`project4_solution.pdf`](./solutions/project4_solutions.pdf)
- [`project5_solution.pdf`](./solutions/project5_solutions.pdf)
- [`final_project_solution.pdf`](./solutions/final_project_solutions.pdf)

---

## Key Takeaways
- **Statistical Expertise**: Gained practical experience in multivariate statistical techniques.
- **Data Analysis**: Improved skills in data preprocessing, visualization, and statistical modeling.
- **Effective Communication**: Presented findings clearly through visualizations and detailed reports.

---

## Contact
- **Name**: Joohyeok Seo  
- **Email**: [jsa184@sfu.ca](mailto:jsa184@sfu.ca)  
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/jacky-seo-7657b4251/)  
- **GitHub**: [joohyeok-seo](https://github.com/joohyeok-seo)
