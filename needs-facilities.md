# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: the sensors are functional
  
  When: the visitor count for a week is available
  
  Then: display a histogram of the visitor count for the week

Scenario: Alert when seating capacity is full

  Given: the sensors are functional and the hospital is functional
  
  When: the sensor count is more than the seating capacity
  
  Then: signal an alert using mail and display board
