# Detection Engineering With Sigma
Building a Detection Engineering lab using Splunk, PySigma, and Sigma Rules.

## Course Overview

This course will provide an introduction to detection engineering under the framework of Sigma rules and how to implement them in your environment. The course will focus on automation and provide the learner with the ability to systematically transform generic detections into complex queries that are customized for any infrastructure.

### Skills

By the end of the course, the learner should have the ability to:
- Read and understand Sigma rules
- Convert rules using the Sigma CLI tool
- Implement the Splunk backend and create scheduled searches
- Implement a custom Splunk application to support Sigma detections
- Build pySigma pipelines to transform generic detections into Splunk queries
- Utilize GitHub to build an automated Detection Engineering ecosystem
- Employ linting and release control techniques on the Sigma rules repository

### Concepts
By the end of the course, the learner should understand:
- The value of open source and community driven detection rules
- The relationship between Sigma rules, pySigma pipelines, Splunk conditional searches, and detection events
- How to use pySigma transformations and conditions to build robust and complex SPL queries
- Building a custom and internal Detection Engineering as Code system that starts with making a PR in GitHub with a new Sigma rule and results in a new event generated for future investigation

## Prerequisites
While this course does provide an introduction to detection engineering, it is expected that students have practical experience in the following realms:
- Able to read Python
- Understand how to modify and apply existing scripts
- CLI Fluency
- Familiarity with Docker
- Familiarity with Windows Event Logs, including Sysmon
- Experience with GitHub Pull Requests and code change management
- Familiarity with Splunk and able to at least make assumptions about the meaning of basic SPL queries such as `index=sysmon DestinationPort=3389 eventID=3`

## Materials/Resources

- A GitHub account
- Visual Studio Code with your GitHub account fully synchronized
