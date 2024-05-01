# SAVIS3 Overview
SAVIS3 is a website built at the request of Prof. Rafael Diaz from Sac State. SAVIS3 aims to provide an open-source educational platform for students around the world to help them better understand statistics. 
This platform provides a myriad of visualization tools, allowing users to actively engage with various statistical concepts and enhance their comprehension. 
![savis_homepage](https://github.com/VaibhavJain2609/savis3/assets/50278167/67b7ceb6-73a3-452b-ae05-f727fab78dba)


<img width="1721" alt="savis_oneproportion" src="https://github.com/VaibhavJain2609/savis3/assets/50278167/f7aa263f-5749-4a19-8397-7f155d7dd0b4">
<img width="1728" alt="savis_regression" src="https://github.com/VaibhavJain2609/savis3/assets/50278167/8d038c7b-e301-4e88-b243-8b650c8ebd91">

### One Proportion Confidence Interval
<img width="1721" alt="savis_regression" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/OPCI.png">
This feature helps in estimating a range where the true population proportion lies based on a sample proportion. Here, we take in success and failure and show the proportion of success and the calculation involves the sample size with a chosen level of confidence (eg., 95%). We are able to see mean, standard deviation, lower and upper bounds of the intervals.


### One Mean Confidence Interval
<img width="1721" alt="savis_omci" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/OMCISS1.png">
<img width="1721" alt="savis_omci" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/OMCISS2.png">
<img width="1721" alt="savis_omci" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/OMCISS3.png">
<img width="1721" alt="savis_omci" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/OMCISS4.png">
One Mean Confidence Interval calculates the confidence interval for the entered data. The first component allows for the data
to be entered into the data. It also displays the count for each point as a scatter plot. The second part takes a sample and
runs the desired simulation. The third section allows for custom upper and lower bound to be added. The fourth section displays
graphs where it checks if it covers the mean of the actual in the sample collected when the bounds are added into consideration.

### Correlation Feature
<img width="1721" alt="savis_correlation" src="https://github.com/VaibhavJain2609/savis3/blob/main/Savis3/src/assets/correlation.png">
This Correlation feature that allows users to analyze the relationship between two sets of data. It provides both manual and file upload options for inputting data and generates correlation coefficients along with visual charts for analysis.

# Timeline

# Testing 
### Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

### Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.
# Deployment 
# Developer Instructions 

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.2.18.

### Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Code scaffolding
Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Further help
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference page](https://angular.io/cli).
