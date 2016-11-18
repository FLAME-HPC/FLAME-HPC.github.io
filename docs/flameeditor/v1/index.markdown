---
layout: default
title: FLAME Editor Documentation
---
## FLAME Editor Screenshot
![FLAME Editor v1 screenshot](../img/flameeditor_v1.png)
The FLAME Editor window contains:
 1. The _Models_ tree which shows the open models and their elements.
 2. The _Memory_ table which shows the memory variables of agents, messages and data types, environment constants and also shows model version, author and description elements.
 3. The _Stategraph_ graph shows the state graphs of agents and models.
 4. The _Transition Function_ table shows the transition functions of agents.

***
## Models
#### New
Click the _New_ button. A dialog appears asking for a file name and location.
New models require a location because any added sub models location depends on its parents location.
 
#### Open model
Click the _Open_ button and using the dialog that appears select the model file.

#### Save model
When a model is selected in the _Models_ tree then click on the _Save_ button to write the model to its associated file.

#### Close model
When a model is selected in the _Models_ tree then click on the _Close_ button to close the model.

#### Edit model name
In the _Models_ tree in the _model_ row double click the _value_ column. This is the model name.

#### Edit model version, author and description
In the _Memory_ table double click rows in the _value_ column to edit the corresponding type.

#### Edit sub models
Sub models can be added by right clicking in the _Models_ tree on a model you would like the sub model added and selecting _Add sub model_.
A dialog appears asking for a file name and location of the sub model.
The sub model is then added to the currently selected model.
The sub model can be enabled and disabled by clicking the tick box associated with it.
The sub model name can be edited by double clicking in the _Value_ column next to the sub model in the _Models_ tree.
The sub model can continue to be edited as if it was a model.
The sub model can be deleted by right clicking on it and selecting from the list _Delete sub model_.

#### Viewing models
A graph representation of models can be seen in the _Stategraph_ graph when a model is selected.
Agent functions that appear in the current model are coloured black.
Any message inputs and outputs of these functions are shown.
Agent functions that do not appear in the current model but appear for example in sub models are coloured grey.
Objects can be moved by using the left mouse button.
The graph can be replot by clicking the _Replot_ button.
To view the graph in a separate window click the _View In Window_ button.
In the separate window the graph can be drawn larger by pressing the _+_ keyboard key and drawn smaller by pressing the _-_ keyboard key.

***
## Environment
#### Edit constants
Constants are displayed in the _Memory_ table. Constants can be added by clicking the _Add Variable_ button.
Any selected row is deleted when the _Delete Variable_ button is clicked.
Double clicking in the _Type_ column provides a list of available types to be selected from.
Double clicking in the _Name_ or _Description_ column allows the editing of these values.

#### Edit function files
Function file locations can be added by right clicking a model in the _Models_ tree and selecting _Add function file_.
A _function file_ is added to the _environment_ of the model in the _Models_ tree.
The location of the _function file_ is edited by double clicking on its _value_ column in the _Models_ tree.
A dialog appears allowing for the selection of the function file.
The relative location of the function file from the current model file is used.
A function file can be deleted by right clicking on it and selecting from the list _Delete function file_.

#### Edit data types
Data types can be added by right clicking a model in the _Models_ tree and selecting _Add data type_.
A _data type_ is added to the _environment_ of the model in the _Models_ tree.
The name of the _data type_ is edited by double clicking on its _value_ column in the _Models_ tree.
The variables of the data type are displayed in the _Memory_ table. They can be edited in the same way _environment constants_ can.
A data type can be deleted by right clicking on it and selecting from the list _Delete data type_.

#### Edit time units
Time units can be added by right clicking a model in the _Models_ tree and selecting _Add time unit_.
A _time unit_ is added to the _environment_ of the model in the _Models_ tree.
The time unit can be edited by double clicking on its _value_ column in the _Models_ tree.
A dialog appears that allows you to edit the time unit.
A time unit can be deleted by right clicking on it and selecting from the list _Delete time unit_.

***
## Agents
#### Edit agents
Agents can be added by right clicking a model in the _Models_ tree and selecting _Add agent_.
The name of the _agent_ is edited by double clicking on its _value_ column in the _Models_ tree.
The description of the _agent_ is edited by double clicking on its _description_ column in the _Models_ tree.
An agent can be deleted by right clicking on it and selecting from the list _Delete agent_.

#### Edit memory
The variables of the agent memory are displayed in the _Memory_ table. They can be edited in the same way _environment constants_ can.

#### Edit transitions
Transitions can be edited either via the _Transition Function_ table or via the _Stategraph_ graph.

##### Transition Function table
_Current State_, _Function Name_, _Next State_ and _Description_ can be edited by double clicking them.
_Input_ and _Output_ can be edited by doubling clicking them. This brings up a dialog which allows the addition and deletion of message types.
Message types can be changed by double clicking and selecting a new type of the list.
For _Input_ the filter can be edited by double clicking under the _Filter_ column. A dialog appears that allows the editing of the conditions.
For _Input_ the sort can be edited by double clicking under the _Sort_ column. A dialog appears that allows the editing of any sorting or randomisation.
_Condition_ can be edited by double clicking which brings up a dialog while allows the editing of the condition.
_Mpost_ is currently not used.

##### Stategraph graph
States are represented by ellipses with their name in the middle.
Functions are represented by rectangles with their name in the middle.
Message types are represented by parallelograms with their name in the middle.
Transitions are shown as black arrows which go from and to states via a function.
Message outputs are shown as green arrows which go from functions to message types.
Message inputs are shown as green arrows which go from message types to functions.
Any function conditions are shown above the function rectangles.
Left clicking on states, functions or message types allows them to be moved with the mouse.
Right clicking on states allows a line to be drawn that represents a transition.
By releasing the mouse button with the end of a line over another state will add a transition function between those states.
By releasing the mouse button with the end of a line not over a state then a new state is added with a transition function between those states.
Right clicking and drawing lines between _functions_ and _message types_ adds inputs and outputs to functions.
Transition functions can be deleted by selecting and clicking the _Delete_ button.
If any objects have been moved, added or deleted from a graph then it can be replot by clicking the _Replot_ button.

***
## Messages
#### Edit messages
Messages can be added by right clicking a model in the _Models_ tree and selecting _Add message_.
The name of the _message_ is edited by double clicking on its _value_ column in the _Models_ tree.
The description of the _message_ is edited by double clicking on its _description_ column in the _Models_ tree.
An message can be deleted by right clicking on it and selecting from the list _Delete message_.

#### Edit variables
The variables of the message are displayed in the _Memory_ table. They can be edited in the same way _environment constants_ can.

***

