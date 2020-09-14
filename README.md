# BeerController
Public repository for LabVIEW Demo: Beer Controller

Alpha Release Features (9/14)
- 4 Different Pours
- Cancel mid pour
- Add/Update Current Beer Selection
- Log in ListBox all actions by users

**Code won't run/do anything if not hooked up to a cRIO....
Notes:
No DQMH implemented yet.  This alpha is to get a working application with minimal features to test user flow and hardware.


Roadmap:
- Implement Database DQMH module for tracking Keg Volume and User use for accounting when Keg needs replacing
- Implement Error Handler Module with an initial just log and keep going to be followed by actual error handling and alerting via email
- Transfer while loops for Producer/Consumer loops to Main UI/RT Modules with added connection handling and safe state for hardware