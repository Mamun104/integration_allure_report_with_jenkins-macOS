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

## Create a job in Jenkins

- We have created a new Maven project “AllureReportWithSelenium_Demo” with the configuration to run the Selenium with TestNG Tests and also to generate Allure Report after execution using Jenkins.

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/10f634d4-df4e-4bb1-b691-7aa521f0227d)

## Execute the tests

- Let’s execute it now by clicking on the “Build Now” button. 

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/76e9af4c-ea11-4706-9503-746704111102)


- Right-click on Build Number (here in my case it is #1).

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/ff3c4454-b063-46f4-bda2-b6f6b33afb3e)

- Click on Console Output to see the result.

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/c07078dd-7cbe-4d44-a4b5-48610e50b46d)


## View the Allure Report

- Once the execution is completed, we could see a link to view the ‘Allure Report’.

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/5d421970-0aeb-4457-9450-3899298f3ec2)

- Click on the Allure Report. It displays the summary of the tests.

## Output

![image](https://github.com/Mamun104/integration_allure_report_with_jenkins/assets/78067017/6e9e98c9-dc91-4b69-ab41-1a6275cee83f)




