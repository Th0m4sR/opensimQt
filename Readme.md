**Important note:**

The project is still under development and is not recommend to use it in its current state. Stable version will be in the Tags tab and links to the binaries will be added. 

------------------------

# opensimQt: a simplified user-friendly opensource and cross-platform cpp interface for OpenSim tool

This is a new cpp interface for the simulation tool [opensim](https://github.com/opensim-org/opensim-core). This interface uses Qt and VTk instead of the current Java netbeans interface. This makes it easier for cpp developers to help with extending and improving this interface as Qt and VTK have better support in the opens-source community.  

Note:
1. Cpp code must be well commented in away that an automatic API documentation is generated by doxygen.
2. Cpp code must have a printing text that print equivalet python script. 
   - For now just printing for debugging until the python milestone completed.    
3. Documentation should have graphs that explain different components.
4. The goal is to simplify the interface developement and extension.
5. Installation should package OpenSim, models and examples.  
6. suggested folders structure
   - vsMain
     - The main interface elements
   - vsCommon
      - Elements needed by different tools 
   - vsSimulation
      - Simulation and Tools    
   - vsVisualiser
      - VTK related elements
   - vsScripting
      - Using PythonQt and VTK python 
      - Python related elements
   - vsExternal
      - Eexternal tools element 
   -vsDocs    
      - Documentation 


In progress (July, August 2020): 

    * implement plugin-function
    * implement inverse kinematic
    * dcomumentation 
    * more customisation
 
The project has 5 milestones:

1. [Building current interface](https://github.com/VisSimKoblenz/opensimQt/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22MileStone+1%3A+Building+the+main+interface%22). (Completed) 
   - [MS0101 create the main qt project with an interface similar to the one in opensim-gui.](https://github.com/VisSimKoblenz/opensimQt/issues/1) 
   - [MS0102: open a .osim file and load its elements to the navigator](https://github.com/VisSimKoblenz/opensimQt/issues/2) 
   - [MS0103: open a .osim file and load its elements to the visualizer.](https://github.com/VisSimKoblenz/opensimQt/issues/3) 
   - [MS0104: open file by drag and drop.](https://github.com/VisSimKoblenz/opensimQt/issues/4) 
   - [MS0105: reload current scene function.](https://github.com/VisSimKoblenz/opensimQt/issues/5) 
   - [MS0106: save functions: scene, model, element.](https://github.com/VisSimKoblenz/opensimQt/issues/6) 
   - [MS0107: close functions: scene, model, element.](https://github.com/VisSimKoblenz/opensimQt/issues/7) 
   - [MMS0108: Visualizer functions](https://github.com/VisSimKoblenz/opensimQt/issues/10)    
2. [Simulation.](https://github.com/VisSimKoblenz/opensimQt/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22MileStone+2%3A+Simulation%22).(Completed) 
   - [MMS0201: implement load motion](https://github.com/VisSimKoblenz/opensimQt/issues/11)    
   - [MMS0202: implement the simulation process](https://github.com/VisSimKoblenz/opensimQt/issues/12)    
   - [MMS0203: Complete simple functions e.g. edit menu and help menu](https://github.com/VisSimKoblenz/opensimQt/issues/13) 
3. [Tools](https://github.com/VisSimKoblenz/opensimQt/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22MileStone+3%3A+Tools%22)
   - add different tools functions
     - Inverse Kenimatics, Inverse Dynamics, ..etc 
   - add plugin function 
   - Plotting:
     - plotting functions
4. [Python](https://github.com/VisSimKoblenz/opensimQt/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22MileStone+4%3A+Python+Scripting%22)
     - implement current python scripting functions
5. [Customisation](https://github.com/VisSimKoblenz/opensimQt/issues?q=is%3Aopen+is%3Aissue+milestone%3A%22MileStone+5%3A+Customization%22)
   - adding new model. (completed)
   - reload current model. (completed)
   - open selected model externally in text editor. (completed)
   - modify model elements e.g. add,edit,remove a body 
   - compare models. 
   - record script function
   - adding transformation function
   - adding registration function
Future work: 
   - starting OpenSim Python Project.
   - starting simpleOpenSim Python Project. 
   - repository for plugins. 
     - users upload the plugin-source code.
     - libraries for Windows, Linux and Mac are built (manually or automatic by a server).


If you like and/or using this project, your support is appreciated, (please cleck Sponsor button above for options). 
