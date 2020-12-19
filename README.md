# UML-Course
UML is an acronym, it stands for Unified Modeling Language.
Provides visual models of how a system is going to interact.
-User behavior
-What the system does
-Tool for problem solving, being able to visualize your code.

Stages of Development where UML is Utilized:
    Activiy Diagram: 
        Allows you to say what happens at each stage of an application's flow. 
        It's a way of being able to break down the flow of an application into v
        ery small manageable chunks.

    Deployment Diagram:
        Gives you the ability to take an incredibly high-level look at your code.
        You can say that I want to have a front end MVC be a Javascript-Angular type 
        of application and I want an API that performs certain tasks and I also want 
        to have a database server along with specific types of elements configured on it.
         You could build out your entire architecture that way.

    Class Diagram:
        During development, you can use Class Diagrams to help you model your entire 
        database to see the relationships between tables and to ensure that you're performing 
        best practices such as database normalization, etc. if you build it prior to building 
        the entire system, you'll find that you're going to have a much more organized approach 
        to modeling your databases.

    Use Case Diagram:
        Use Case Diagrams are very high level and allow you to organize each of the processes 
        a specific user of the system is allowed to access. When I'm building an authorization 
        system I can check to see the different features that users or that type of user should 
        have access to. By utilizing a Use Case Diagram, it allows me to take a visual approach.
        It also is something I can use to show non-technical stakeholders to ensure that I'm 
        building the system in the right way.

    Sequence Diagram:
        Lastly, after the entire application has been built, UML can still play a very helpful role. 
        For example: if I have to build in a more advanced feature or refactor something that was built 
        awhile ago, I can use what's called a Sequence Diagram. Sequence Diagrams are able to see all of
        the messages the system is passing internally to ensure that I'm building my methods in an efficient 
        way and I'm following best practices so I can implement something that'll actually work in the system.

    Package Diagram:
        After the entire system has been built, there are times where I personally go look at the 
        code base and see how I can organize it be more efficient or I want to decrease the coupling 
        between different modules. I may take out one part of the entire application and turn it into 
        an outside code library. To do that, I can use a Package Diagram to see how I'm organizing the
        entire code base. That also gives me a very high-level overview for every component in the 
        system and allows me to make sure that I'm conforming to best practices. If I bring a new member
        to the team, I can show them that Package Diagram and they'll be able to see how the entire system
        is organized.

UML Components and Common Elements:
    Six common elements shared across various diagrams:
        -Frames
        -Classifiers
        -Stereotypes
        -Comments
        -Dependencies
        -Features (which are also called Properties)

UML Components: FRAMES: 
    -Help you encapsalate your view components
    -Provides Context
    -Headings
    -Descriptive notation
    -Provides context
        ++You want to know exactly what type of system it represents.
        ++You want to know what type of diagram it is.
    Diagram mapping:
    act = activity
    class = class
    cmp = component
    dep = deployment
    sd = interaction
    pkg = package
    stm = state machine
    uc = use case

UML Components: CLASSIFIERS:
    -Allow us to identify components. A category of components we see in every kind of diagram
    -High level design
    -Standardized naming convention as you start building out your designs
        Used by:
        -Class
        -Interface
        -Association
        -DataType
        -Actor
        -Use Case
        -Artifact
        -Component
        -Signal

UML Components: COMMENTS and NOTES:
    -Common UML components are comments. 
    -Also called "Notes,"Ability to have descriptive markup.
    -In a rectangular box with dotted line to element
    -Communication clarity for anyone reading it
    -Explanations outside of normal scope

UML Components: DEPENDENCIES:
    -Denotes coupling. Gives abilty to see how badly one component needs another component
    -Dotted line with open arrow
    -Model required components 
    -Regression error prevention
    -ie. Song request class that communicates with API. Needs API to work
        *SongRequest - - - -> SpotifyAPI

UML Components: FEATURES and PROPERTIES:
    -Represents attributes of an element
    -Name and optional attributes
    -Implementation guidance
    -Establish standarized/strict naming convention
===============================================================================
                                New Section
===============================================================================
High level overview of each of the major types of diagrams that are offered by UML

 -Two Categories: 
    Structural diagrams:
        Are any type of diagrams that model the way a system is architected.
        A class diagram is one of the most popular structural diagrams out there. 
        It's a way of defining the different class names, attributes, and method 
        names that belong inside of a system that you're building.
            -CLASS: 
            Pick out what type of data you want, how you want those elements 
            to be associated with each other, and some of the core operations.
                *Name
                *Attributes
                *Operations

            -DEPLOYMENT:
            Gives us the ability to model how an entire system architecture should be configured.
            If we have an application that has multiple servers, multiple places where we can store 
            code and it's going to communicate with the system, a deployment diagram is perfect for 
            setting that up. ie. Deployment engine for stages of production
            Made up of six components:
                *Nodes 
                *Components
                *Artifacts
                *Links
                *Dependencies
                *Associations

            -PACKAGE:
            Great to use for code libraries you want to build an application with.
                *Classifer
                *Class
                *Use Case
                *Type
                *Component
                *Package
                *Constraint
                *Dependency
                *Event

    Behavioral Diagrams:
        It cares about different things like what type of messages does one system send to another or 
        Behavioral diagrams are much different, behavioral diagrams care about how your system behaves.
        what types of permissions does user A have versus User B. Those are the types of questions that
        you're going to model out inside of behavioral systems.
        Made up of four components:
            *Activity
            *Use Case
            *State machine
            *Sequence

        Activity Diagrams: 
           -Activity diagrams are very easy for non-technical users to see and understand
           -More high level than class diagram on theh structual side
           -Allows you to look at a board and see what the system is supposed to do from start to finish
           -User Experience: what does it look like for the user
                *Initial State or Starting Point
                *Activity or Action State
                *Action Flow
                *Decisions or Branching
                *Guards
                *Final state or End Point
        
        Use Case Diagram:
            They give you the ability to show everything that a user has access to. I like to use Use Case diagrams 
            when I'm building out an application and I need to illustrate an authorization system. I want to show 
            what users can do and what admin users can do.
                *Use cases
                *Actors
                *Subsystems
                *Relationships

        State Machine Diagram:
            The state machine diagram is a very old concept in CS.
            What is being visualized is what data looks like and actions
            at various stages of a software systems lifecycle.
            Breaks things down into very small pieces for what should
            be occuring.
                *Entry Point
                *Choices
                *Constraints
                *States
                *Transitions

       Sequence Diagram:
            Sequence diagrams are a common diagram that many senior-level developers like to use. 
            They speak directly to the implementation. They speak to how the code needs to operate.
            If done well, it will make the implementation of the project much easier to build. 
            Important for setting up inputs and outputs. Helps understand behavior of system.
                *Class Roles or Participants 
                *Activation or Execution Occurance
                *Messages
                *Lifelines  

    Class Diagram Elements:
        Three elements previously covered:
            *Name
            *Attributes
            *Operations

        Attributes have three different items at a minimum that you should include:
            *Visibility
            *Name
            *Data Type

   Class Diagram Associations:    
        *Association: 
            -How one class is connected to another
            *ie.
                -Guide belongs to topic
                -Topic had many guides
                -A guide has many and belongs to tags
                -A tag has many and belongs to guides
        *Multiplicity:
            -How we designinate the direction of the relationship in regards to numbers
                Topic: 1 Guide: 1..*    1..*     0..* Tag
        *Navigability
            -How you can take one class and have it communicate with any other classes.
            -This sets the rules for knowing how that communication can take place.
            *ie. 
                -You cna find all of the guides for a topic
                -You can find all of the tags for a topic through a guide
                -You can find a guide's topic
                -You can find all tags associated with a guide

        



