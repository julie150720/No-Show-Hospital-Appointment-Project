# No-Show-Hospital-Appointment-Project

In this project, we will investigate the No-show appointments dataset, and predict which factors will affect the no-show appointments. This original dataset collects information from 110.527 medical appointments in Brazil and is focused on the question of why patients do not show up for their appointment. This is a Kaggle competition, which can be found from here: https://www.kaggle.com/datasets/joniarroba/noshowappointments

   
Feature Selection:
Lasso Regression
![image](https://user-images.githubusercontent.com/68930546/183460198-93c023e2-ae7e-4c82-9ea3-2554cded4bc4.png)

Feature Selection: Recursive Feature Elimination

![image](https://user-images.githubusercontent.com/68930546/183460115-40743eba-4ca8-4b8c-9f78-bedb6d98da1e.png)

One of the factors affecting the no-show appointment is the duration between the booking date and appointment date. The patients have many reasons not to attend the appointments such as significant work or family commitments; therefore, it is hypothesized that the waiting period is positively associated with the missing appointments. 

   The second influential factor is the patient’s missed appointment history, which is the cumulative sum of prior no-show appointments. If the patients used to miss the appointment previously, it is hypothesized that they will continue missing the appointments. 

   The third impactful factor is the age of the patient. When the patient is older, he/she is less likely to miss the hospital appointment, as their health are associated with more risks. Parsons et all also concluded in their research that patients less than 21 years old are more likely to miss the appointment2. Therefore, it is hypothesized that the age of the patient is negatively associated with the missing appointments.

   The fourth factor might impact the no-show appointment is whether they are new patient or existing patient. Marbouh et al3 mentioned in their research that the no-show appointment rate is higher among new patient visits. 
