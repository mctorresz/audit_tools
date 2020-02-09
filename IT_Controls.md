# General Controls (Data Reliability) #

## System Layers (Example): ##
- Application: PeopleSoft
- Database: Oracle
- Server: Unknown, not mainframe
- Network: Active Directory

## Procedures: ##
### Minimum for each data set: (4 hours) ###
- Completeness - count program matches results, or observe query running
- Reasonableness - does code produce the results provided?
	- Critical to ensure no items are incorrectly excluded
 
### Recommended for each application: (12 hours) ###
- Application screen user access review (who has write/modify access to those screens?)
	- Reasonable and necessary?
	- Typically involve business area individuals.
	- Consider whether departments have reasonable access. Example, Communications doesn’t need access to Finance budget records.
- Do periodic access reviews occur?
	- Application admin review (who can modify access?)
	- Database backend user access review
 
### Full scope: ###
- Server user access (4 hours)
	- Possibility to manipulate system information
- Network high profile user access (2 hours)
	- Network admin have access to all systems via desktops
	- Minimal usefulness for most audits, but easy to test via data analysis
- For each layer, do periodic access reviews occur?
	- Typically used to complement the cause in user access findings
- Maintenance:
	- Change management (12 hours)
		- Does necessary system maintenance occur?
		- Are emergency changes approved?
	- Backup/recovery processes (DRP/business continuity) 
		- If system is not backed up/secure, then reliability is compromised
	- Scheduled jobs (4 hours)
		- Who monitors?
		- How are ABENDS handled?
 
## Application Controls ##
- Edit checks (control activity)
	- In test environment, test effectiveness by attempting to enter incorrect data.
	- If test environment is not available, do not test
- Routing/approvals (control activity)
	- What approvals/routing controls are in place?
	- In test environment, test effectiveness by creating a transaction and observing it to completion.
	- If possible, review example for audit trail
- Reporting (monitoring)
	- Does management, IT or Business Area, produce any reports to periodically (at least annually) verify that data is being input accurately?
	- An example is needed with evidence of review or control doesn’t exist.
