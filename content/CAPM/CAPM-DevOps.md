---
title: "CAPM - DevOps"
metaTitle: "How a DevOps process could look like for CAPM apps on SAP BTP."
metaDescription: ""
---


# When should I use it?

- When the company has a DevOps process in place.
- When automated tests are required and/or have to be enforced.
- When manually building and deploying applications is not acceptable.
- When tests and deployments need to produce audit logs.

# Footnotes

- HTML5 Application Repository Service can host any web app such as SAP Fiori, Angular, React, Vue, etc.
- CAPM (Cloud Application Programming Model) apps could be developed in Node.js or Java.
- Communication between the services should go through the Destination Service, not added to the diagram to simplify it.
- On-premise solutions could be both SAP and non-SAP.
- Cloud solutions could be both SAP and non-SAP.
- SAP Cloud Identity Services is not required to connect to On-premise or Cloud solutions.

# Examples

- Developer creates a CAP app with Node.js + SAP Fiori + SAP HANA artefacts.
- Developer pushes the code to a git repository.
- SAP BTP CI/CD Service is triggered via a webhook from git.
- It builds and tests the application.
- All tests passed, the application is deployed to subaccount QAS.

# Image

![devops](https://github.com/rsletta/sap_btp_icons_drawio_lib/assets/443888/8fe02f70-ef0d-4a73-bf1b-16e197b598ee)

# Tags / Keywords

CAP, CAPM, Node.js, Java, cTMS, CICD, DevOps, Business Application Studio


[Open Diagram](https://app.diagrams.net/?create=https://raw.githubusercontent.com/rsletta/sap_btp_icons_drawio_lib/main/src/templates/CAPM-DevOps/SAPBTP-CAP_DevOps.drawio.xml)