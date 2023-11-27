We are archiving this repository because we do not want learners to push personal development to the current repository. If you have any issues or suggestions to make, feel free to:
- Utilize the https://knowledge.udacity.com/ forum to seek help on content-specific issues.
- [Submit a support ticket](https://udacity.zendesk.com/hc/en-us/requests/new) along with the link to your forked repository. 
- If you are an enterprise learner, please [Submit a support ticket here](https://udacityenterprise.zendesk.com/hc/en-us/requests/new?ticket_form_id=360000279131)

## Give your Application Auto-Deploy Superpowers

In this project, you will prove your mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

For your submission, please submit the following:

- A text file named `urls.txt` including:
  1. Public Url to GitHub repository (not private) [URL01] https://github.com/rupesh291/udacity-cicd-project/
  1. Public URL for your S3 Bucket (aka, your green candidate front-end) [URL02]
  1. Public URL for your CloudFront distribution (aka, your blue production front-end) [URL03]
  1. Public URLs to deployed application back-end in EC2 [URL04]
  1. Public URL to your Prometheus Server [URL05]

<h2 href="#Screenshots">Screenshots</h2>
<ol>
<li>
  <h4>Backend build failed. SCREENSHOT01 </h4>
  <img src="./ScreenShots/Screenshot01 Bankend build failed 2023-11-26.PNG">
</li>
 <li>
  <h4>Backend build failure. SCREENSHOT02 </h4>
  <img src="./Screenshots/Screenshot02 Test backend failure 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Job that failed because of vulnerable packages. SCREENSHOT03 </h4>
  <img src="./Screenshots/Screenshot03 Scan backend failure 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>An alert from one of your failed builds. SCREENSHOT04 </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Appropriate job failure for infrastructure creation. [SCREENSHOT05] </h4>
  <img src="./Screenshots/Screenshot05 Ec2 AMI failure 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Appropriate job failure for the smoke test job. [SCREENSHOT06] </h4>
  <img src="./Screenshots/Screenshot07 Smok test failure.PNG">
</li>
 <li>
  <h4>Successful rollback after a failed smoke test. [SCREENSHOT07] </h4>
  <img src="./Screenshots/Screenshot08 Rollback on failure.PNG">
</li>
 <li>
  <h4>Successful promotion job. [SCREENSHOT08] </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Successful cleanup job. [SCREENSHOT09] </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Only deploy on pushed to `master` branch. [SCREENSHOT10] </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage. [SCREENSHOT11] </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
 <li>
  <h4>Provide a screenshot of an alert that was sent by Prometheus. [SCREENSHOT12] </h4>
  <img src="./Screenshots/Screenshot04 Email Alert 2023-11-26 191512.PNG">
</li>
  
- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)
