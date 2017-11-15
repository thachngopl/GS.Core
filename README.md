# GS.Core
  Core functions shared by several projects (Bus, theading, Reference (Key<>Value pair) storage.)

- GS.Bus : 
  Implements threaded based minibus : Able to make inter thread communication easely. (See demo)
  Could be used for MVVM based architecture. GS.Bus is used in Grid System internal Grid Server.

- GS.LocalMemCached : 
  Mimic in an app MemCached server (in a way...)

- GS.Reference : 
  Base chunck for Key<>Value pair file storage system. Used in GS.LocalMemCached.
  
- GS.Task
  Task management with communication system between task.

# Dependancy

  For FPC : github.com/dathox/generics.collections

# Demo

  Demo for GS.Bus and GS.Task are currently provided for Delphi 10.2 VCL
  
  GS.Bus : 
  ![Alt text](/../master/Ressources/GSBusBenchVisual.png?raw=true "GS.Bus Bench demo")
  
  GS.Task : 
  ![Alt text](/../master/Ressources/GTaskBenchVisu.png?raw=true "GS.Bus Bench demo")
