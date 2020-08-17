# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given the count before server downfall is available 
  
  When the server restarts
  
  Then display the count as the count just before downfall of server

Scenario: Reconcile counts if the sensor is offline for a while

  Given the sensor is offline
  
  When there is a visit
  
  Then count all the visits during the sensor is offline manually and update it 
