#Use Case 1

**Title:** Retrieve OSS license and known Vulnerability information for components identified in a submitted package 

**Primary Actor:** Manager

**Goal in Context:** The Manager must be able to retrieve stored information on OSS licenses and Security Vulnerabilities associated with specific software components, the Developer will be submitting the relevant packages to the system.

**Stakeholders:** Developer and Manager

**Preconditions:** The Developer needs to send a package to the sub system so the components can be identified and each one processed for vulnerabilities and then for licenses

**Main Success Scenario:** Submitted information is accurate within the Database so it can be properly queried

**Failed End Scenario:** The manager receives no report or the report is missing relevant records

**Trigger:** Manager sends a request for relevant information
