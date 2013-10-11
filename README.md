Veeva-Cycle-Plan-Set-Status
===========================

Batch process to handle cycle plan activation/inactivation. Allows load of cycle plans in advance of the given cycles.


How to Run
--------------
	Option 1. Run manually via the SFDC Developer Console:
	database.executebatch(new VEEVA_PS_SET_CYCLE_PLAN_STATUS (),200); 
	
	Option 2. Schedule a nightly routine, preferably before the 
	Cycle plan calculation routine. 
	Setup > Develop > Apex Classes > Schedule Apex
