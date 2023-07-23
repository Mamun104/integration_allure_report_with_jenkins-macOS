# Integration of Allure Report with Jenkins


## Implementation Steps

- Download the Allure Jenkins Plugin
- Configure Allure
- Create a new Maven Jenkins job

## Configure Allure

- Go back to the Manage Jenkins link as shown below:
  

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/055e404a-1ddb-4158-9df3-c7862b9fbc6a)


- When we click on the “Manage Jenkins” link, we are redirected to the Manage Jenkins page, where we can see various types of options, including the “Global Tool Configuration” option.
  

  ![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/29a5595e-2e81-47cf-8dda-f24516d3e34e)


- We need to set the Allure Commandline in Jenkins as shown below.


![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/2de2eb65-9024-419a-ae77-ef83a7630d71)


- Click on the Allure Command line installations button. By default, “Install Automatically” will be checked, so since we are going to use the Allure installed on our local machine, “Install automatically” will install the latest version of Allure.

- Provide the Name as ALLURE_HOME because that is what is currently installed on my machine, and also provide the path of Allure in the ALLURE_HOME textbox.


![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/9bd56235-1622-40bd-8234-0d3158742a95)

- Click on the Apply and save buttons

