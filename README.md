# CloudFormation-ThreeTierWebApp
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- ABOUT THE PROJECT -->
## About The Project

### Sample Three Tier Architecture for Web Application
###### (Scripts have a sequential order to be ran, VPC script goes first and then RDS script.)
Three Tier Architecture has become a staple practice for many Web Application solutions when it comes to deploying a highly available and scalable application. This three-tier-architecture deploys a VPC with 2 Availablitiy Zones, 6 subnets, 2 public and 4 private, along with 2 NAT gateways, an Internet Gateway, public and private route tables, an S3 bucket for any packages or files, and deploying 2 database instances in the database-tier one on each AZ.

CloudFormation is a service by AWS that is used to provision AWS resources using code. When you create a stack, AWS will automatically go through your code and deploy the resources you defined automatically which makes provisioning infrastructure very easy and neat! CloudFormation scripts can be written in yaml or JSON but in this lab I chose to write it in yaml because it is very easy to read and define all the resources you need when writing the script. 

Why CloudFormation?
* It is an AWS native solution for Infrastructure as a Code and does the job of automatically provisioning resources well. 
* Terraform can be a good alternative.
* Writing the code is very easy since AWS supplies a lot of documentation for problems or templates you might need.

Still in progress, so what is next?
* Writing new scripts that deploy needed components into the subnets. (Bastion Host, ELB, ALB, Auto-Scaling Group, Client Server, Web Server)

### Built With

* [![AWS][AWS]][AWS-url] [CloudFormation](https://aws.amazon.com/cloudformation/)


<!-- CONTACT -->
## Contact

* [![LinkedIn][linkedin-shield]][linkedin-url]

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Resources you should use if you want to try it out too!

* [AWS Source by Rick Armstrong](https://aws.amazon.com/blogs/compute/re-platform-java-web-applications-on-aws/)
* [Article by Kinsey Parham](https://levelup.gitconnected.com/create-a-3-tier-architecture-via-aws-cloudformation-b25e450e8acd)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/lap-le-cloud/
[project-screenshot]: images/screenshot.png
[AWS]: https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white
[AWS-url]: https://aws.amazon.com/
