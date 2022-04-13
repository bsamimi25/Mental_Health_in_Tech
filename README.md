# Mental_Health_in_Tech

  <p align="center">
<img width="500" src="https://user-images.githubusercontent.com/67808057/163098432-0708f9e6-d527-4912-8318-b24874b48a4f.jpeg">
  
This project is based on the dataset from a *2014 survey from Open Sourcing Mental Illness* that measure attitrude towards Mental Heath and the frequency of Mental Health disorders in the tech workplace. 

# Overview 
  
My project will be focused on the perspective of the tech employee and if they are comfortable with their employer to discuss topics such as their Mental Health. I will use Python to clean and manipulate from given data to create visualizations to determine the perspective of the tech employee. 

# Data Cleaning Process

  I decided to import my data into my Python file from my local Postgresql Server. After importing, and after a brief glance, I tacked my changes as follows:
- Deleted *State* and *Timestamp* columns 
- NA values where not functioning properly, replaced with 'No Answer' 
- Dropped irrelevant Ages 
- Made 3 Gender categories 
- Made a Continent column
- No_Employees Column was formed into 5 categories
 
# Results
  After my data cleaning process, I now had a cleaned dataset ready to be utilized for Data Analysis. 
  
  The goal of this project was to determine the perspective of the tech employee by gender. In order to do so, these are the specific columns I want to explore. 
 
 Main Columns:
  - **Gender** : Men,Women,Other
  - **Age**: Integer
  - **Mentalhealthconsequence** : Do you think that discussing a mental health issue with your employer would have negative consequences?
  - **Coworkers** : Would you be willing to discuss a mental health issue with your coworkers?
  - **Supervisor** : Would you be willing to discuss a mental health issue with your direct supervisor(s)?
  - **Mentalhealthinterview** : Would you bring up a mental health issue with a potential employer in an interview?
  - **Seek_Help**: Does your employer provide resources to learn more about mental health issues and how to seek help?
  
  
  Primary Analysis:
  
  - We can see that, on average the tech employee is uneasy about talking about their mental health with their employer. 
  - The high count of "Maybes" shows that there is some unknown aspect to the tech employees perspective. Specifcally, Men seem to be most uneasy               with this conversation with their employers. 
  
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163101024-45a92c80-3a60-480e-ac28-444c643f6263.png">
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163102906-2e64d6f2-e6fd-4fbf-b1e9-e34d7b9c1b0d.png">
     
   Lets check the percentages for all Genders:  
     
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163103367-aa5da7a6-0fbb-4a41-83e9-531c6dacc0d3.png">
    
   Lets explore the average of our Age column to determine the types of employees are answering these questions. 
    
    - Average: ~ 32 years
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163102536-9465e26a-32eb-4fd8-9306-206dc7f1a406.png">
    
    
  Secondary Analysis:
    
    Gauge more into the tech employee mindset by exploring the *Coworker* and *Supervisor* Columns. 
    
    - We can see there are some similarities with all Genders, in terms they speak about their Mental Health with closer coworkers
    - Men are more open to talk about their Mental Health with their direct Supervisor 
    compared to Women who are even across the graph, yet seek less Treatment compared to Women, who are more willing to be treated
    - In total, we see there is a reluctancy to speak to their direct supervisor about their Mental Health 
    - Most employees, are not willing to get help with their Mental Health
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163104849-600b4340-1b10-487e-bf8c-4d7ef56a3b21.png">
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163105016-af2d0d8e-8163-494e-8929-45f60a27ec79.png">
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163106734-a236b6c8-1587-47bd-af22-f5fa5ecb63d1.png">
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163105227-58298dea-e37c-4689-ad92-caee1967c71e.png">
    
  <p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/67808057/163107444-6d58a541-503b-4c48-836a-3ebff1b03c79.png">
    
    
# Summary
    
   After performing these visualizations, I have gotten a good sense of what the average tech employees perspective is when it comes to Mental Health. To start, we can easily see their is an uneasiness with the topic of Mental Health among the workforce. Why is that? Is there a stigma around not showing "Weakness" around expressing yourself and being honest with your employer? Seems like tech employees are more open to talk about their Mental Health with their close coworkers but are more reluctant to speak to their direct supervisor. Unfortunately, we also see tech employees do not have much options fom their employer to seek treatment for their Mental Health. I beleive if tech employers provide more outlets to their employees for self care and to improve their Mental Health, productivity and efficiency will be improved. This has been glimpse into the perspective of the tech employee and unfolded the sad truths and potential solutions to improve upon. Thanks for reading!
