# TItle

## Requirement analysis
elaborate on basic requirement of the sistem and buold some basic models.
We dont care how to do stff. we care of what we can do. with a high level of abstraction
example

username provides the password 
then => the requirement analyssis have 4 possible models:
1. Scenario based model.
2. Class-oriented models: more technical (not shown to the customer).
3. Behavior of the system.
4. Flow model: data model.

## Rules of Thumb
- model should focus on requirement and task the system does with a high level of abstraction
- Provie the models thaT describe all use cases
- Delay considertrion of infrastructures (mysql, js, vue...)
- Mynimaze coupling throught system. (reduce and dived work)
- Models provide values to all people involved into the project 
- KISS

## Pattern Analysis
When starting the requirement fases. Check if similar problems have been solved or try to solved in the past. 

## Scenarion-Based models
Use cases are simply an aid to define what exists outside the system and wwhat should b eperformed.
but how:
1. write about what
    - Inception and allicitation => provide you with the information you'll need writing use cases.
    - Requirement s gathering meetingd and othe requirements are used to
        - identify stakeholders
        - define scope of the problem
        - specify overall operational goals
        - ...
2. how much should we write
    - Very informal description of how the tsk should be done
    - In general, ....
3. How detailed should the description be
4. How should the description be 

## Developing a Use case [^12] - [^14]
Homeowner
- Select camera to view
- Request thumbnail from all cameras
- Display camera views from a specific camera 
- Control pan and zoom for a specific camera
- Selectively record  camera output
- Replay camera out put
- access camera surveilance

## Exceptions
- describe different situations. 

## Use case diagram
Its a draw that we provide for the customer comeposed 2 parts:
- Users
- Systems
- External component (opional)
If something is repetitive, then use an **include** task figure.

## Activity diagram
> A graphical representation of the scenarios
Similar to the flow charts.
The start is represented by a big dot, and the end as well expet that is circled.
In between use *ovals* to represent the action in the activity diagram. If something is done in parallel the diagram can show with a **black square** which forks out into the task done at the same time.
The **black square** is also used to represent items that *join together* and must be done before going to the next step.
The **if** is represented by a **romboid**.

## 





