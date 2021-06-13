# Airbus DevSecOps Challenge

As told, I have used the following project [**DVA**](https://github.com/CSPF-Founder/JavaVulnerableLab/) (Damn Vulnerable Applications) project, which I found in OWASP Vulnerable Web Applications Directory and forked in here. 

## Important Links
[**Click Here**](https://github.com/dasgourav/devsecops-airbus/blob/master/CloudformationTemplate/Master-template-to-build-end-to-end-DevSecOps-pipeline.yaml) to check the **Cloudformation Master Template** which brings up the below Reference Architecture.

[**Click Here**](http://54.208.205.1:9000/dashboard/index/devsecops-airbus) to open the **SonarQube Dashboard**.

[**Click Here**](https://automationking.s3.amazonaws.com/report-20210613184356.html) to open the **SAST Report**.

[**Click Here**](https://automationking.s3.amazonaws.com/1623610969.xhtml) to open the **DAST Report**.


## Objective:
Thus, the objective here is to demonstrate how to incorporate SAST, DAST and Code Quality in a DVA project to look for vulnerabilities and flag issues through an automated CI/CD pipeline on a Cloud Environment. I have used my [open-source project](https://hackernoon.com/devsecops-introduction-clear-instructions-on-how-to-build-a-pipeline-in-aws-part-1-5nx334e) to achieve this. 

## How Does it Work:
The tutorial has used open-source tools to build the DevSecOps pipeline to make the demo more achievable. The below diagram depicts the tools and native services used along with the security control gates applied in the process. Also, the reference architecture is provided below.

![alt text](https://raw.githubusercontent.com/dasgourav/devsecops-airbus/master/Reports/DevSecOps_Tools.jpg)

![alt text](https://raw.githubusercontent.com/dasgourav/devsecops-airbus/master/Reports/DevSecOps_Arch.png)
