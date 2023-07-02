# Mattia Colombo, PhD

_Platform/DevOps engineering lead @WBA, Integraction CoE -- UK based_

[Email](mailto:colombomattia89@gmail.com) / [LinkedIn](https://linkedin.com/in/colombomattia89) / [GitHub](https://github.com/mattcolombo)

## Skills and Technologies

**Apache Kafka and Confluent Cloud** <br>
  - Administration of various Kafka clusters in Confluent Cloud (PaaS)
  - Definition of best practices and naming conventions for Kafka assets such as topics, connectors and schemas
  - Access management, including RBAC, for Confluent Cloud Portal
  - Deployment and management of various ancillary components (Confluent Control Center, Kafka Connect, ksqlDB) both on cloud VMs using Ansible and Kubernetes using Helm
  - Automation of some workflows around creation of topics, service accounts and ACLs in Confluent Cloud using various tools such as kafka‑admin and julie (a GitOps tool for Kafka)
  - Installation and management of Connector plugins in Kafka Connect, including deployment and configuration of various types of connectors
  - Created scripts and CLIs for more convenient management of Kafka Connect leveraging the Connect REST APIs
  - Provide advice to Kafka developers and architects in project teams both within and outside of Integration as the local SME
<br><br>

**Kubernetes** <br>
  - Management of various applications deployed on Kubernetes, both through command line (kubectl and the Kubernetes API) and in an automated fashion using Helm
  - Development and management of Helm charts for the deployment of various ancillary and utility applications to facilitate monitoring and alerting of other applications in Kubernetes and elsewhere
  - Pipelines for management of secrets using Azure KeyVault and the azure CLI in combination with the Kubernetes API
  - Troubleshooting and analysis of applications running in Kubernetes using the Kubernetes API and tools
<br><br>

**Platform/DevOps Engineering Lead** @[WBA](https://www.walgreensbootsalliance.com/), Integraction CoE _(June 2021 - Present)_ <br>
  - Provisioning and management of the self‑hosted components of Apigee Hybrid
  - Management and definition of naming conventions and best practices for environments and virtualhosts for Apigee Hybrid
  - Identity and Access Management (IAM) for Google Cloud projects and Apigee access, including analysis and creation of custom roles for specific access requirements
  - Automation of Apigee provisioning, in particular for environments and virtualhosts as well as the complete provisioning process
<br><br>

## Project Highlight

**Kafka Connect management CLI** [kafka-connect-cli](https://github.com/mattcolombo/kafka-connect-cli) <br>
This is a project I worked on in my spare time outside of work. I created a CLI to manage Kafka Connect, get information about the cluster, workers and various assets deployed on the cluster and manage them. I decided to start working on this because in my day job I was always struggling with managing effectively Connect. The product offers a very good and complete Rest API that can be used to manage virtually all aspects of the product; working directly with the API is however quite slow and inefficient, so I set out to write a CLI following the style of the `kubectl` and `confluent` CLIs that could manage at least the most common aspect of Connect. As a secondary motive, I wrote the CLI in GO, using it to learn the language; since this is the language that Kubernetes and many modern cloud technologies use, it is a good idea to be at least somewhat familiar with it.

Since the CLI uses the Rest API under the covers, it will work independently of the specific Kafka Connect implementation (such as any vendor implementations) as long as the host running theCLI has connectivity to the Connect cluster Rest API and the implementation allows the access to manage Connect through the Rest API.

## Professional Experience

**Platform/DevOps Engineering Lead** @[WBA](https://www.walgreensbootsalliance.com/), Integraction CoE _(June 2021 - Present)_ <br>
In my technical lead role I am responsible for prototyping and proof of concepts for new technologies the business wishes to implement. I am also in charge of setting best practices across the engineering team and helping the engineers in the team follow them in the best way possible for each new technology that gets introduced
  - I work closely with the platform technical architects and the platform Product Owner to set the roadmap for our team and help set and review the work of the team
  - As before I spend some of my time working with the SA/development teams (both internal to the Integration CoE and external) in the early stages of a project, coaching them in the use of the platform, and helping them achieve the best possible results
  - Currently working with management and in close contact with the RunOps teams in the company to establish an improved support model for the platform and agree on roles and responsibilities; this will also include coordinating the knowledge transfers from our team to the support teams
  - Together with management I helped establish the best practice for external and internal teams to engage with platform engineering in an efficient way that is beneficial for everyone without impacting too much my team's goals and objectives
  - Together with the other tech leads and our team manager, I have been responsible for building a fantastic diverse team, with all the skills we require to succeed in our mission
<br><br>

**Platform Engineer** @[WBA](https://www.walgreensbootsalliance.com/), Integraction CoE _(October 2020 - June 2021)_ <br>
  - Initially drafted in the cloud platform engineering team to develop the company's Kafka strategy and as the primary point of contact for the initial vendor interaction with Confluent
  - As the Kafka/Confluent SME in the team, I was initially mainly responsible for development and roll-out of best practices and ways of working around Confluent products
  - Responsible for building and maintaining in the WBA Azure cloud subscription the ancillary technologies to augment our use of Confluent Cloud. Main examples are Kafka Connect, ksqlDB and Confluent Control Center, deployed both in Azure VMs and k8s
  - Expanded my role to work with all the vendor technologies in our team, including the first deployment of Apigee Hybrid to our k8s services, and the build and maintenance of Qlik Replicate, installed on Windows servers
  - Big part of my role is also to interface with development team to discuss their requirements and coach them in the way the platform works, in order to enable them to follow best practices and prevent false starts with the development
<br><br>

**Graduate Software/DevOps Engineer** @[WBA](https://www.walgreensbootsalliance.com/) _(October 2018 - September 2020)_ <br>
  - Collaborated in the initial implementation of our automated deployment framework including all the technology stack used within the Integration CoE in the Azure cloud
  - Produced independently a Proof of Concept aimed at expanding the capabilities of our automated deployment framework for SoftwareAG webMethods to include additional types of assets
  - Collaborating in the transformation effort of the structure of Software Engineering within the Integration CoE. Main task was to try aligning standards (eg naming conventions and versioning) and ways of working across the technology stacks and across all teams
  - Some experience working leading a small group of off-shore developers to deliver our business goals
  - Worked in close contact with our teams near-shore and off-shore to achieve business goals
  - Part of the Graduate programme run by Boots UK
<br><br>

**Science Teacher (KS4/5), Physics specialisation** @[NUAST](https://nuast.org.uk/) _(September 2017 - August 2018)_ <br>
  - Physics teacher working with both GCSE and A-Level students
  - Secondary responsibility as tutor for a Year 12 group, including helping to apply for University and writing cover letter and recommendations
<br><br>

## Qualifications and Certifications

  - **Confluent Certified Administrator for Apache Kafka**; obtained March 2023 [Verify me](https://www.credential.net/93b99ab4-f2ce-4d39-992a-dab8641b9f08)
  - **AZ900 - Microsoft Azure Fundamentals**; obtained March 2023 [Verify me](https://www.credly.com/badges/e2e19827-ed8a-4ddb-b6a3-d10d8674d424)
  - **Oracle Certified Associate - Java SE 8 Programmer**; obtained November 2019
  - **scrum.org Professional Scrum Master I**; obtained December 2019
  - **BCS Lvl.4 Diploma in Software Development Methodologies**; obtained July 2019
  - **TOGAF 9 certified**; obtained May 2019

## Languages

**English:** fluent
**Italian:** native

## Education

**Level 4 Apprenticeship in Software Development** @[Boots UK](https://www.boots-uk.com/) and [Firebrand](https://firebrand.training/uk/) _(January 2019 - August 2020)_ <br>
As part of the Graduate Scheme in Software Engineering at Boots UK. Awarded a final grade of _Distinction_.
<br><br>

**Postgraduate Diploma in Education (PGDE)** @[Nottingham Trent University](https://www.ntu.ac.uk/course/education-teacher-training/) _(September 2016 - August 2017)_ <br>
Course in Secondary Sciences, with specialisation in Physics.
<br><br>

**PhD in Mathematical Physics** @[School of Mathematical Sciences, University of Nottingham](https://www.nottingham.ac.uk/mathematics/) _(October 2013 - December 2016)_ <br>
Performed research on alternative theories of gravity, their geometrical structure and the effects on observations for various consological scalar fields. Produced six papers published in international journals.
Final thesis on _Aspects of Lorentz violating theories of gravity_ also publicly available on [Nottingham University ePrints](https://eprints.nottingham.ac.uk/38419/).
<br><br>

**Masters Degree in Physics** @[University of Trento](https://www.unitn.it/) and [SISSA/ISAS](https://www.sissa.it/) _(October 2011 - September 2013)_ <br>
Graduated "Summa Cum Laude" with a final dissertation on _Relativistic BEC: a Dark Matter Candidate_
Dissertation published in the Journal of Cosmology and Astroparticle Physics ([JCAP](https://iopscience.iop.org/article/10.1088/1475-7516/2014/02/004))
<br><br>

**Bachelor Degree in Physics** @[University of Trento](https://www.unitn.it/) _(September 2008 - September 2011)_ <br>
Graduated with a final dissertation on _Absolute Negative Temperatures_
