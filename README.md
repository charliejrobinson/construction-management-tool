# Construction management tool
A tool to schedule tasks for construction built by Charlie Robinson. Using the principles of critical path analysis, tasks are ordered by dependency and a schedule created. Tasks can be viewed, added, removed, and edited using a GUI implemented in PyQT as shown below.

# Interface

![GUI interface](https://github.com/charliejrobinson/construction-management-tool/blob/main/Interface.PNG)

## Annotations
 1. Project name input box 
 2. Worker number input box  
 3. Activity name input box 
 4. Activity duration input box 
 5. Dependencies selection box 
 6. Activity table
 7. File menu for accessing 
 8. Schedule (only appears once schedule has been pressed) 
 9. Delete buttons for activities
 10. Add activity button
 11. Schedule button
 
 

## Installing
Unzip directory and then
`$ cd Scheduler-0.1`
`$ pip install .`

## Running
`$ python bin/scheduler-gui`

### Tests
`$ python setup.py test`

## Creating package
`$ python setup.py sdist --formats zip`

## Notes
Example database included for better viewing
