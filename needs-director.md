# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given: the report is available
  When: the aggregate is available
 Then: display the patient count of working days and holidays 

Scenario: Compute parking slots to reserve for visiting specialists

  Given: the count of specialists visiting
  When: the available parking slots is less than required parking slots
  Then: relocate some vehicles from the parking slot to other locations
