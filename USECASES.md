#Use Cases

##Use Case 1

###Title: 

Determine License and Vulnerability Information for Software Project

###Primary Actor: 

-Manager

-Developer

###Goal in Context:

The manager or developer are able to determine the license and vulnerability information for the software project in question.

###Stakeholders:

-Manager receives clear and relevant information of the software project.

-Developer receives clear and relevant information on the software project containing the packages they submitted.

-Project owner is able to understand the decisions of their managers based on the project information.

###Preconditions:

-Relevant information concerning the software project is contained in the OSS database.

-Correct information has been provided when attempting to access the licenses and vulnerabilities associated with a software project.

###Main Success Scenario:

Manager or developer receives accurate license and vulnerability information for the requested software packages that make up their software project.

###Failed End Conditions:

-Software project contains packages that are not in the OSS database.

-Incorrect information is entered in the request for licenses and vulnerabilities of a software project.

-Inaccurate or invalid license and/or vulnerability information for the requested project packages is returned.

###Trigger: Manager of developer identifies project information to which licenses and vulnerabilities are provided.

##Use Case 2

###Title: 

Submit Software Package to the OSS Database

###Primary Actor:

Developer

###Goal in Context:

A software package will be sent through the manage software package for license/vulnerability scanning process to be scanned for licenses and for vulnerabilities in the NIST vulnerability database.  Once this package is scanned it will be sent back through the same process and be added to the open source software database.

###Stakeholders:

-Developer: Provides access to a software package in the OSS Database successfully.

-Manager: Able to retrieve information about software package being added to the database if done successfully.

###Preconditions:

-A developer must have a new software package for submission.

-The software package mustn't have already been added to the OSS database.

-The software package must have open source software licensing.

-The software package must be listed in the NIST vulnerability database.

###Main Success Scenario:

A software package is submitted by a developer to be scanned for licensing and NIST Vulnerabilities, the results of this scan are added to the OSS Database.

###Failed End Conditions:

-The software package is alread in the OSS database.

-The software package is not licensed or licenses are innacurate.

-NIST Vulnerability database returns no results for the software package or vulnerabilities are innacurate.

###Trigger:

Developer submits a software package to be scanned for licenses and vulnerabilities, this package is then added to the OSS database.

##Use Case 3

###Title:

Manager submits or modifies policy documents to the OSS policy document database

###Primary Actor:

Manager

###Goal in Context:

Managers create or change policies regarding open source software licenses and vulnerabilities.

###Preconditions:

-Manager wants to create a policy for software projects.

-Policy changes require that there already be a policy in place in the OSS policy document database.

###Main Success Scenario:

The manager wishes to create or modify a policy in the OSS policy document database.  These submissions are sent through a process that forwards the submissions into the OSS policy document database.

###Failed End Conditions:

-Can't modify policy if policy document isn't already in the database.

-Manager does not plan to change or create policy documents.

###Trigger:

A manager creates or changes policy documents regarding the licenses and vulnerabilities of a software package.  These are sent through a process then to the OSS policy document database for storage and future retrieval.
