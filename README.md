prior-scientific-stage-control-csharp
=====================================

Customize-able user stage control for Prior Scientific stage and driver, written in C# .NET framework in MS Visual Studio

Created by Derek Gann on Dec. 4, 2012
Last updated on Jan. 9, 2013
Contact Derek.Gann@colorado.edu

This software was developed using the Prior DLL provided by Prior Scientific in their download center. The sofware was written in C# using the .NET framework. The files come with Visual Studio 2010 project/ solution files.

Be sure to verify that the movement parameters and stage limitations are compatible with your stage before testing, otherwise erratic behavior may result if values are not compatible. Most, if not all, values are in micrometers and microseconds, but all units should be labeled.

The code was developed and is provided because Prior Scientific neglected to provide example source code for a stage controler in a language other than NI LabVIEW. The main file is reasonably well commented and should be pretty straight forward. It provides fine control over Prior stage XY-stepper motors for precise positioning. It includes gathering stage connection and movement parameters, motion limits/ boundaries for the stage, maximum and minimum step sizes, user defineable origin, a return to origin button, a return to true center button, a readout of stage current position, a readout of stage state, and a readout of connection and stage-information status. Also included is a stepwise scanning function with user defined step size, dwell time/ step duration, scan area, scan type, starting position of scan, an option to set the origin to scan start pos., and an option to return to scan start position.

This should be enough to get you started with text-based programming for a Prior stage controller. Enjoy not having to use LabVIEW. I sure do. :)
