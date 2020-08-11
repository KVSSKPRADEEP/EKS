# EKS
1.Abstract


Our main job of test execution depends on how successful the deployment was. If the deployment team faced challenges and encountered several issues and couldn’t deploy the code properly, it will surely indicate the QA team is going to identify a lot of bugs that may be tied to the environment or deployment process.
If Testers are aware of the deployment process, they will understand the importance of completing their tasks within the planned time-frame.
Testers will get an idea if the issue is really a functionality bug or something caused during deployment say a tester is assigned to test the report feature but when he tries to log in to the website, he is seeing an error which means the environment is down, such issues cannot be considered as functional issues but as environmental. If the tester is aware of the deployment, he can relate the issue to be a deployment issue. Many non-issues could be avoided if the testers really are aware of the list that got deployed. Sometimes it does happen you test and reports an issue for areas that never were deployed. The entire test design phase takes place before the code is actually moved to the environment. It’s the test execution that depends on the code availability in the QA environment while the Deployment team works on getting the code deployed in QA, the QA team should ensure to have completed. And we are in the world of rapid development and in order to keep the client requirement and delivering it client as quick as possible is the main requirement of the industry these days, because the more quick you are deploying decides the Overall growth of your company handling it. And keeping that in mind we proceeded with this project of automation.


 
2.Project Description


Our society has been growing rapidly and in order keep ourself in pace with it. We started on this project of developer side deployment with all the testing neccessities given. Because your website is your hub for making sales. And your site's aesthetic and style are equally as important as the purchasing experience your customers go through. In this day and age, that means that new, innovative products must keep pace with the marketplace. Product development lifecycle times are becoming shorter and shorter to keep up with customer’s expectations and needs. While perhaps daunting, a short lifecycle can optimize your company’s strengths by tightening processes and cutting out extra steps. And we have taken Kubernetes (K8s) an open-source system for automating deployment, scaling, and management of containerized applications. And for organizations that want to participate in bringing awareness to Kubernetes have been increasing and in this project we have integrated the two big technologies into my project i.e Cloud environment and using up the Kubernetes as service we basically do this project as a return on investment type because the code written once can be used for other projects to deploy our requirement. And in just a click of a btton we can deploy our own website with own storage, scaling, and all the requirements for a website to run.






3.Technology Used


Kubernetes:

Kubernetesis an open-source container-orchestration system for automating computer application deployment, scaling, and management. Kubernetes defines a set of building blocks ("primitives"), which collectively provide mechanisms that deploy, maintain, and scale applications based on CPU, memoryor custom metrics. Kubernetes is loosely coupled and extensible to meet different workloads. This extensibility is provided in large part by the Kubernetes API, which is used by internal components as well as extensions and containers that run on Kubernetes.The platform exerts its control over compute and storage resources by defining resources as Objects





Amazon Web Services:

Amazon Web Services (AWS) is a subsidiary of Amazon that provides on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis. In aggregate, these cloud computing web services provide a set of primitive abstract technical infrastructure and distributed computing building blocks and tools. One of these services is Amazon Elastic Compute Cloud (EC2), which allows users to have at their disposal a virtual cluster of computers, available all the time, through the Internet. 



4.Data Used


Terraform is an open-source infrastructure as code, software tool created by HashiCorp. It enables users to define and provision data center infrastructure using a declarative configuration language known as HashiCorp Configuration Language (HCL), or optionally JSON.Terraform manages external resources, such as public cloud infrastructure, private cloud infrastructure, network appliances, software as a service, and platform as a service, with "providers". HashiCorp maintains an extensive list of official providers, and can also integrate with community-developed providers. Users can interact with Terraform providers by declaring resources or by calling data sources. Terraform has a great set of features that make it worth adding to your tool belt, including:
Friendly custom syntax, but also has support for JSON.Visibility into changes before they actually happen.Built-in graphing feature to visualize the infrastructure.
Understands resource relationships. One example is failures are isolated to dependent resources while non-dependent resources still get created, updated, or destroyed. Open source project with a community of thousands of contributors who add features and updates. The ability to break down the configuration into smaller chunks for better organization, re-use, and maintainability. The last part of this article goes into this feature in detail. We have under gone with data of terraform and proceeded with the project.
