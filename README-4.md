
-**Part Two: Behavioral Diagrams:** 

    -Behavioral Diagrams:
        -It cares about different things like what type of messages does one system send to another.
        -Behavioral diagrams care about how your system behaves.
        -IE. What types of permissions does user A have versus User B. 
            **Made up of four components:**
                *Activity
                *Use Case
                *State machine
                *Sequence

    -Activity Diagrams: 
        -Activity diagrams are very easy for non-technical users to see and understand
        -More high level than class diagram on the structual side
        -Allows you to look at a board and see what the system is supposed to do from start to finish
        -User Experience: what does it look like for the user
            *Initial State or Starting Point
            *Activity or Action State
            *Action Flow
            *Decisions or Branching
            *Guards
            *Final state or End Point
    
    -Use Case Diagram:
        -They give you the ability to show everything that a user has access to. 
        -Good to use when you need to illustrate an authorization system. 
        -Show what users can do and what admin users can do.
            *Use cases
            *Actors
            *Subsystems
            *Relationships

    -State Machine Diagram:
        -The state machine diagram is a very old concept in CS.
        -What is being visualized is what data looks like.
        -Actions at various stages of a software systems lifecycle.
        -Breaks things down into very small pieces for what should be occuring.
            *Entry Point
            *Choices
            *Constraints
            *States
            *Transitions

    -Sequence Diagram:
        -A common diagram that many senior-level developers like to use. 
        -They speak directly to the implementation. 
        -They speak to how the code needs to operate.
        -If done well, it will make the implementation of the project much easier to build. 
        -Important for setting up inputs and outputs. Helps understand behavior of system.
            *Class Roles or Participants 
            *Activation or Execution Occurance
            *Messages
            *Lifelines 