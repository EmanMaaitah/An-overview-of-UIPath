## OBJECTIVE
[UiPath](https://www.uipath.com/)
The main purpose of UiPath is to automate Windows desktop chores.With support for drag and drop, UiPath offers a user interface that is simple to use.
UiPath is used to automate repetitive operations and minimize or eliminate the need for human involvement in them.

## Interface components
1) [UiPath Studio](https://docs.uipath.com/studio/standalone/2024.10), used for RPA developers.

2) [UiPath StudioX](https://docs.uipath.com/studiox/standalone/2023.10), used for business users.

   *You can change between them > Settings > License and Profile >  Change Profile


     <img src="https://github.com/user-attachments/assets/7267f72d-fece-4aae-915f-c8e1d2c2cb2d" width="450">

 ## UIPATH TOOLS
1) [Orchestrator](https://docs.uipath.com/orchestrator/automation-cloud/latest), is a web application that enables you to orchestrate robots in executing repetitive business processes.
2) [UiPath Assistant](https://docs.uipath.com/robot/standalone/2023.4/user-guide/about-uipath-assistant), it is an application used on desktop.
    *UiPath Studio is used for developing and publishing automation workflows, whereas UiPath Assistant is used for running the automations.
    * You can publish your project on Orchestrator or UiPath Assistant using publish library in design tap > choose publish options > publish to 


    <img src="https://github.com/user-attachments/assets/57daaa82-692a-4e55-99d3-069180166403" width="450">

  ## UIPATH PANELS
  ### UPPER PANELS
1) Ribbon Tabs
   * Home: Go to the Studio Backstage View where you can open and create projects
   * Design:
      -First groub: New, Save Export as, Debug file (Debug, Run, Run file)
      -Second groub: Manage pakages (To insert a new extentions)
      -Third groub: App/Web Recorder, Computer Vision, User Events, Table Extraction.
      -4th groub: UI Explorer, Remove unused , Analyze file
   * Debug:

   <img src="https://github.com/user-attachments/assets/24f5b4ed-4d8c-42ad-bef5-630ebc0b0df8" width="600">  
   
        -Step Into (activity by activity), Step Over(container by container) , Step Out
        -Retry re-executes the previous activity, error are shown in the Locals and Call Stack panels
        -Ignore, ignore an encountered exception
        -Break, Focus Execution Point
        -Slow Step This is similar to using Step Into, at 1x runs it the slowest, and fastest at 4x
        -Execution Trail,Show execution status
           green;executed activities are marked
           not marked; not executed
           red; error
     
  ### MIDDLE PANELS
2) Designer Panel : Workspace
  ### LEFT PANELS
3) Project Panel: contents of your current project, manage files, folders, and dependencies.
4) Activities Panel:Resources and Actions
5) Snippets Panel:Use pre-built workflows.

  ![image](https://github.com/user-attachments/assets/a451227f-b80d-42f6-aa5a-cceb2b3dffd3)

  
  ### BOTTOM PANELS
6) Variables Panel:create variables and make changes to them.
7) Arguments Panel:enables you to create arguments
8) Imports Panel


   <img src="https://github.com/user-attachments/assets/6ea5c223-fc03-488b-b9d0-4093e2037d1c" width="450">
  


9) Output Panel:you can always filter the messages displayed in the Output panel by simply selecting the alert types of interest, or even clear all messages.
10) Error List Panel: displays errors
11) Breakpoints Panel:pause the debugging process on an activity which may trigger execution issues
  ### RIGHT PANELS
12) Data manager Panel: manage various types of data, Variables, Arguments Entities.
13) Test Explorer Panel
14) Autopilot Panel
15) Outline Panel: hierarchy of the current workflow
16) Properties Panel:configure the properties
17) Objrect Repositories Panel:UI taxonomies

   ### Panels that only visible during debugging
18) Locals Panel:displays properties,Properties of previously executed activity 
Exceptions , Arguments, Variables

   ![image](https://github.com/user-attachments/assets/18d251c7-d8b5-4655-b924-e3c840715deb)


19) Watch Panel: values are updated after each activity execution while debugging
20) Immediate Panel: evaluate variables, It cannot be modified
21) Call Stack Panel: displays the next activity

   ![image](https://github.com/user-attachments/assets/63c8e9ea-e724-4ad8-b632-d5dd4879d530)



## There are three ways to deal with errors in uipath
1) Continue on error
2) Global Exception Handler
3) Try Catch

## RPA Life Cycle
  discovery, design, development, testing and deployment.

  ![image](https://github.com/user-attachments/assets/d242725d-dbed-4fd1-8510-1a00688c0486)

















 
