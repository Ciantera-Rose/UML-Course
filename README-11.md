**UML State Machine Diagram Elements**

    -State machines are one of the earliest types of concepts 
     in computer science.
    -Goal is to visualize what the application (or what a feature of the application) 
      will like and how it can transition from one state to another state.
    -The main goal is to visualize the state of whatever object
      we're trying to follow
    -Acitvity diagram are sililar but work more like a flow chart. A State machine cares
     more about the different actions that can chnage a users state

    -Entry Point:
        *From the exaplme, it is that large filled in black dot and 
            that is the start.
        -If you're building a web or a mobile application it's when 
            the user gets to the page or sees the screen. 
        -If you're building an API or something like that, it's when 
            the request comes in and they pass the information in. That's the start of the system and that black dot is how it's represented.

    -Choice:
        *Choices are where questions are being asked.
        *Choices are represented by the 45-degree angle square.
        *Checking for how the state will change

    -Constraint:
        *The "Yes and the "No"
        *This was called the guard in pervious diagrams
      
    -State:
        *One of the most important parts of the entire diagram
        *They are represented by the rounded edge rectangle
        *ie: A user that is a visitor and a user that has been converted

    -Transition:
        *The transition is how you get from one state to another
        *Represented by a line with an arrow showing the direction 
         of that transition.
        *May also have other items like choices, that are placed 
         in between those
        *There's typically something that you're checking for,
         maybe some value they have to enter or something specific about their account. If we're talking about users here, that allows them to transition from one state into the next one.



