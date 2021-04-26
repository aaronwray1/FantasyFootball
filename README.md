# Fantasy Football :soccer:

## Planning and Requirements Analysis

### Requirements

* The web application should allow a user to create an account
* The web application should allow a user to log in 
* The web application should allow a user to sign out of their account
* The web application should allow a user to delete their account
* The web application should allow a user to create their squad
* The web application should allow a user to save their squad
* The web application should allow a user to view their squad
* The web application should allow a user to delete their squad
* The web application should allow a user to transfer players in/out of their squad
* The web application should allow a user to choose their starting 11
* The web application should allow users to select substitutes
* The web application should display the images of players




## Defining Requirements
### Software Requirement Specification
### Risk Assessment

| Risk                                                             | Likelihood | Severity | Control Measure | Response                                                        | Revisit Date |
| ---------------------------------------------------------------- | ---------- | -------- | --------------- | --------------------------------------------------------------- | ------------ |
| A user obtains access to an account that does not belong to them | Low        | High     | Prevent         | Hash with a salt all passwords within users database            | N/A          |
| A user accidentally deletes their account                        | Low        | High     | Mitigate        | Ask for additioional confirmation before the account is deleted | 06/2021      |
| A user accidentally deletes their squad                          | Low        | Medium   | Mitigate        | Ask for additioional confirmation before the squad is deleted   | 06/2021      |

## Design
### Design Document Specification
