# Super Cool Computing Company (SCC)

## Mission

Contract work for creative industries - Film, TV studios, game dev etc.

## Website Only Stack

Used to create promotional websites. Uses external API's for some integration.

- **Languages:** Astro, ReactJS, JavaScript
- **Version Control:** GitHub (External read only access for clients)
- **CI/CD:** GitHub Actions, email approved deployment
  - Privately staged website sent to client for approval, automatically deployed publicly upon approval
  - Work compiled, deployed to private URL and sent to client at end of each day automatically?
- **Containerization:** Not specified, assume none
- **Cloud Hosting:** Netlify
- **Auto Scaling:** Not specified, assume none
- **Load Balancing:** Not specified, assume none

## API Stack

Web API's created for undefined various client requirements. Mentions they can provide file handling and storage

- **Languages:** JavaScript, TypeScript, C#
- **Version Control:** Not specified, assume also GitHub
- **CI/CD:** Not specified, assume none
- **Containerization:** Not specified, assume none.
- **Cloud Hosting:** Deployed to Google Cloud Platform (GCP), running in virtual machines (EC2 instance equivalent). Runs 24/7, claims high uptime.
- **Auto Scaling:** Not specified, assume none
- **Load Balancing:** Not specified, assume none
- **File Storage:** No mention of file storage hosting technology used, assume AWS S3 equivalent on GCP

## Other Considerations

- No mention of infrastructure as code (IAC)
- Claims they can work with existing API's, require cloud migration strategy?
- Claims they use automated tests, but say "Developers run tests themselves each day to be sure that their work is on the right track."

Assessment Purpose
Before spending time and resources on a project, it’s crucial to understand what technologies a product should be built with and why. This applies to all parts of a software project, including devops.
To solidify your knowledge of modern software development concepts and show your understanding of devops technologies and software architectures, you should be able to appropriately suggest suitable software, services or development techniques to facilitate devops practices in an application.

Assessment Task / Item
For this assessment, you must submit a PDF file with content that meets the requirements to showcase your skills as a software developer.

Assessment Instructions
Given the provided case study, write a proposal in report format to implement a new DevOps practice. Your
proposal should focus on the benefits to the case study organisation, and include:

1. Containerisation
2. Cloud services
3. Continuous integration/continuous delivery (CI/CD)

Report requirements

1. Explain the core concepts of:
   ○ cloud computing
   ○ containerisation
2. Identify and explain the devops elements and technologies that:
   ○ are currently used by the case study organisation, including their containerisation, cloud
   services & continuous integration/continuous delivery (CI/CD) stack.
   ○ not used but should be as per your proposal and suggestions.
3. Identify and explain the business functions and impacts that:
   ○ the current implementation or lack of implementation of devops has on the case study
   organisation.
   ○ the proposal and suggested changes would bring to the case study organisation.
4. Create an application architecture diagram (AAD) that depicts your proposed suggestions
   ○ Write an explanation of the AAD that justifies each change and explains the components of
   the diagram

Assessment Rubric

| Task Descriptor                                                                                                                                            | (HD) High Distinction (85-100%)                                                                                                                                                      | (D) Distinction (75-84%)                                                                                                                                            | (C) Credit (65-74%)                                                                                                                                        | (P) Pass (50-64%)                                                                                                                                                    | (F) Fail (0-49%)                                                                                                              |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| IDENTIFIES devops elements & technologies used by a business or organisation (10%)                                                                         | Correctly IDENTIFIES five (5) or more devops elements or technologies used by a business or organisation.                                                                            | Correctly IDENTIFIES four (4) or more devops elements or technologies used by a business or organisation.                                                           | Correctly IDENTIFIES three (3) or more devops elements or technologies used by a business or organisation.                                                 | Correctly IDENTIFIES two (2) or more devops elements or technologies used by a business or organisation.                                                             | Does NOT identify any devops elements or technologies used by a business or organisation, or only identifies one (1).         |
| EXPLAINS devops elements & technologies used by a business or organisation (15%)                                                                           | EXTENSIVE explanation of NUMEROUS devops elements & technologies used by a business or organisation.                                                                                 | MODERATELY-DETAILED explanation of NUMEROUS devops elements & technologies used by a business or organisation.                                                      | EXTENSIVE explanation of ONE devops elements & technologies used by a business or organisation.                                                            | MODERATELY-DETAILED explanation of ONE devops elements & technologies used by a business or organisation.                                                            | Fails to explain any devops elements or technologies used by a business or organisation.                                      |
| IDENTIFIES devops business functions & impacts relevant to a business or organisation (10%)                                                                | Correctly IDENTIFIES five (5) or more devops business functions & impacts relevant to a business or organisation.                                                                    | Correctly IDENTIFIES four (4) or more devops business functions & impacts relevant to a business or organisation.                                                   | Correctly IDENTIFIES three (3) or more devops business functions & impacts relevant to a business or organisation.                                         | Correctly IDENTIFIES two (2) or more devops business functions & impacts relevant to a business or organisation.                                                     | Does NOT identify any devops business functions & impacts relevant to a business or organisation, or only identifies one (1). |
| EXPLAINS devops business functions & impacts relevant to a business or organisation (15%)                                                                  | EXTENSIVE explanation of NUMEROUS devops business functions & impacts relevant to a business or organisation.                                                                        | MODERATELY-DETAILED explanation of NUMEROUS devops business functions & impacts relevant to a business or organisation.                                             | EXTENSIVE explanation of ONE devops business function or impact relevant to a business or organisation.                                                    | MODERATELY-DETAILED explanation of ONE devops business function or impact relevant to a business or organisation.                                                    | Fails to explain any devops business functions & impacts relevant to a business or organisation.                              |
| EXPLAINS core concepts & applications of cloud computing (10%)                                                                                             | EXTENSIVE explanation of NUMEROUS core concepts and NUMEROUS applications of cloud computing.                                                                                        | MODERATELY-DETAILED explanation of NUMEROUS core concepts and NUMEROUS applications of cloud computing.                                                             | EXTENSIVE explanation of AT LEAST ONE core concepts and AT LEAST ONE applications of cloud computing.                                                      | MODERATELY-DETAILED explanation of AT LEAST ONE core concepts and AT LEAST ONE applications of cloud computing.                                                      | Fails to explain any core concepts & applications of cloud computing.                                                         |
| EXPLAINS core concepts & applications of containerisation (10%)                                                                                            | EXTENSIVE explanation of NUMEROUS core concepts and NUMEROUS applications of containerisation.                                                                                       | MODERATELY-DETAILED explanation of NUMEROUS core concepts and NUMEROUS applications of containerisation.                                                            | EXTENSIVE explanation of AT LEAST ONE core concepts and AT LEAST ONE applications of containerisation.                                                     | MODERATELY-DETAILED explanation of AT LEAST ONE core concepts and AT LEAST ONE applications of containerisation.                                                     | Fails to explain any core concepts & applications of containerisation.                                                        |
| DEVELOPS an application architecture diagram that depicts appropriate improvements to the cloud architecture of a provided application or case study (15%) | MULTIPLE application architecture diagrams provided, representing MULTIPLE appropriate improvements to a cloud application’s architecture with MULTIPLE cloud architecture patterns. | MULTIPLE application architecture diagrams provided, representing MULTIPLE appropriate improvements to a cloud application’s architecture.                          | ONE application architecture diagram provided, representing MULTIPLE appropriate improvements to a cloud application’s architecture.                       | ONE application architecture diagram provided, representing ONE appropriate improvement to a cloud application’s architecture.                                       | Diagram either not provided or not depicting any or much relevant appropriate data about the application’s architecture.      |
| EXPLAINS appropriate improvements to the cloud architecture of a provided application or case study (15%)                                                  | EXTENSIVE explanation of ALL improvements of a cloud application architecture diagram & how the components of that architecture interact with each other.                            | MODERATELY-DETAILED explanation of ALL improvements of a cloud application architecture diagram & how the components of that architecture interact with each other. | EXTENSIVE explanation of SOME improvements of a cloud application architecture diagram & how the components of that architecture interact with each other. | MODERATELY-DETAILED explanation of SOME improvements of a cloud application architecture diagram & how the components of that architecture interact with each other. | Explanation provided is either completely incorrect, not containing relevant details, or not provided at all.                 |
