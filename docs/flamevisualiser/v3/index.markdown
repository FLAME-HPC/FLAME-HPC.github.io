---
layout: default
title: FLAME Visualiser Documentation
---

## Config Files
#### New config
Click File on the menubar and select _New_. A dialog appears asking for a file name and location.
New config files require a location because the location of results data is relative to the config location.

#### Open config 
Click File on the menubar and select _Open..._ and using the dialog that appears select the config file.

#### Save config
Click File on the menubar and select _Save_.
To save as a different file then select _Save As..._ and using the dialog that appears select a file.

#### Close config
Click File on menubar and select _CLose_.

## 1. Location of Results Data
#### Select the location
Either directly edit the location text box or click the _Find..._ button and use the dialog that appears to select the directory.

## 2. Visual Rules
#### Add a rule
Click the _Add Rule_ button and a default row is added to the visual rules table.

#### Delete a rule
Click the _Delete Rule_ button and any selected rule is deleted from the table.

#### Select agent type
Each rule relates to an agent type that is to be visualised.
Double click the _Agent Type_ cell and using the combo box select an agent type.
The agent types are automatically read in from results files that have been successfully read.

#### Select a condition
Sometimes you only want to visualise certain agents from a given type.
By double clicking on the _Condition_ table cell using the dialog that appears you can enable a condition and set it.
A condition is currently an agent memory variable related to a numerical value by a logic operator.

#### Set X, Y and Z
The position in Cartesian space on the x, y and z axes can be set by double clicking the _X_, _Y_ or _Z_ table cells.
The position can depend on agent memory variables or a numerical value or both.

#### Select shape
Double click the _Shape_ table cell and a shape dialog appears.
Using the dialog the shape can be set and its size.

The quality of spheres being drawn affects the speed of the visualiser. To make the visualiser faster reduce the quality of the spheres. Also if any large spheres look blocky then increase their quality.
8 - low quality
16 - medium quality
32 - high quality

#### Enable/disable a rule
The last _Enable_ column allows you to enable or disable rules easily.

#### Open/close visual window
Click on the _Open Visual Window_ button to open the visual window.
To close the visual window either click the _Close Visual Window_ button or click the close button on the visual window or press the _esc_ key.

#### Spin the visual model
Hold the left mouse button over the visual window and move the mouse or use the arrow keys.

#### Zoom the visual model
Hold the right mouse button over the visual window and move the mouse up and down.

#### Change the Near Clip Plane
The near clip plane can be changed by holding down the C key and the right mouse button and moving the mouse up and down.

#### Pick an Agent
An agent can be picked and its memory displayed by holding down the P key and left mouse clicking on an agent. The agent picked is highlighted.

#### Move the Centre of the Visual Scene
The scene can be shifted up, down, left and right by holding down the _spacebar_ and the left mouse button and moving the mouse.

#### Restricting Drawing Axes
By selecting 'Restrict Axes' from _Visual_ on the menubar the drawing of agents can be restricted on the x, y and z axes. When the minimum value sliders are fully to the left and the maximum value sliders are fully to the right those restrictions are turned off.

#### Perspective and Orthogonal view
By selecting _Perspective_ or _Orthogonal_ from _Visual_ then _View..._ on the menubar the view can be changed.

## 3. Graph plots

## 4. Time step

