# TIAX project for generating UR5e control libraries

This project contains multiple SIMATICAX generated libraries for interaction with a UniversalRobot via Profinet

## TIAX Workflow for generating libraries
  If not done, login to the AX registry
  (Optional at startup) Update of all packages implicitly

   ```sh
   apax update -a
   ```

  To build project
  ```sh
   apax build 
   ```
   To create libraries:
   ```sh
   apax create-tialib 
   ```

## Generated libraries
--> Enable robot --> Checks for availability of robot; Enables robot if available
--> State Machine --> State machine for overall station