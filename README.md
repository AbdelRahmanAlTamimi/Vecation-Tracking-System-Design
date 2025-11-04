# the vision
1- empower every employee with the tools and responsibility to independently manage their time-off — including vacation, sick leave, and personal days — without needing detailed knowledge of company or local leave policies.
2- streamline the functions of the human resources (HR) department, to minimize noncore, business-related activities of management
3- improve the internal business processes of this organization, at least with respect to the time it takes to manage vacation time requests.

# non-funtional requierment
- easy to use
- run in any HTML 3.2 capable browser
- implement single-sign-on

# Functional Requirements
- Implements a flexible rules-based system for validating and verifying leave time requests
- Enables manager approval
- Provides access to requests for the previous calendar year, and allows requests to be made up to a year and a half in the future
- Uses e-mail notification to request manager approval and notify employees of request status changes
- Keeps activity logs for all transactions
- Enables the HR and system administration personnel to override all actions restricted by rules, with logging of those overrides
- Allows managers to directly award personal leave time (with system-set limits)
- Provides a Web service interface for other internal systems to query any given employee’s vacation request summary


# Constraints 
- we should deliver the system as a web app
- implemented as an extension to the existing intranet portal system, and uses the portal’s single-sign-on mechanisms for all authentication
- Uses existing hardware and middleware
- never open a transaction in one page and close it in another
- Interfaces with the HR department legacy systems to retrieve required employee information and changes
- use Central Authenticatoin Service to identify and authenticate end users.



# Assumptions

