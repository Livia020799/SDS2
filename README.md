# Statistical Methods in Data Science & Laboratory II
This repository hosts the final project (***`SDS2_final_prohject---JAGS`***) for Statistical Methods in Data Science & Laboratory II exam, held by Professor Luca Tradella, as part of the Master’s degree in Data Science at Sapienza University of Rome.

-------------------------------------------------------------------------------------------------------------------------------------

### **Exam Structure**

The exam for Statistical Methods in Data Science & Laboratory II comprised one individual homework assignment, a midterm exam covering the first half of the course, and a take-home exam for the second half.<br>
This repository contains the details of the final project component of the course.

-------------------------------------------------------------------------------------------------------------------------------------

### **Project Overview**

From ***SMDS-2-Final-Project-Guidelines.PDF*** uploaded in this GitHub repository you can see the project guidelines. <br>

The project investigates the influence of community dynamics and social norms on crime rates. By examining factors such as socio-economic stability, family structure, and public assistance, it aims to reveal how collective community behaviors affect criminal activity. Using the **Communities and Crime** dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/183/communities+and+crime), the study explores these variables, focusing on **Per Capita Violent Crimes** as the target. The data was preprocessed to ensure consistency, with normalization applied to align variable distributions.

The analysis employed both Bayesian and frequentist approaches:

- **Bayesian Hierarchical Model**:<br> This model, leveraging both fixed and random effects, uses a beta distribution for the crime rate variable. It includes interaction terms to capture complex socio-economic relationships, with results indicating significant predictors like family structure, economic investment, and public welfare. Posterior predictive checks and diagnostics, such as the Deviance Information Criterion (DIC), confirmed the model's robust fit.

- **Frequentist Generalized Linear Mixed Model (GLMM)**:<br> A GLMM was applied to assess similar relationships between community characteristics and crime. The model encountered minor heteroscedasticity issues, which were mitigated through data transformations. It identified comparable key predictors, with consistency in family and economic stability's impact on reducing crime rates.

Both models suggest that cohesive family structures, stable income levels, and supportive welfare policies contribute to lower crime rates. The Bayesian model, through interaction effects, highlights how compounded socio-economic challenges exacerbate crime, while the GLMM confirms these insights with frequentist techniques.

These insights underscore the importance of community cohesion and socio-economic support in reducing crime rates, suggesting that interventions focused on family stability and economic equity can effectively mitigate crime.

-------------------------------------------------------------------------------------------------------------------------------------

### **Exam Score and Project Usage**

**This project (plus the homeworks) contributed to my final exam score in the full "Statistical Methods in Data Science" exam (12 CFU)**. It helped me **increase my score from 27/30 in the first part of the exam to a full 30/30 as the final grade**. Feel free to use it as a reference if you are planning to take the exam in the upcoming years.<br> 
Please do not hesitate to contact me if you need further explanations or encounter any issues with the materials.



 


