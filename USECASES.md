#Use Cases

##Use Case 1

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
