# UML-Course
UML is an acronym, it stands for Unified Modeling Language.
Provides visual models of how a system is going to interact.
-User behavior
-What the system does
-Tool for problem solving, being able to visualize your code.

Stages of Development where UML is Utilized:
    Activiy Diagram: 
        Allows you to say what happens at each stage of an application's flow. It's a way of being able to break down the flow of an application into very small manageable chunks.

    Deployment Diagram:
        Gives you the ability to take an incredibly high-level look at your code.
        You can say that I want to have a front end MVC be a Javascript-Angular type of application and I want an API that performs certain tasks and I also want to have a database server along with specific types of elements configured on it. You could build out your entire architecture that way.

    Class Diagram:
        During development, you can use Class Diagrams to help you model your entire database to see the relationships between tables and to ensure that you're performing best practices such as database normalization, etc. if you build it prior to building the entire system, you'll find that you're going to have a much more organized approach to modeling your databases.

    Use Case Diagram:
        Use Case Diagrams are very high level and allow you to organize each of the processes a specific user of the system is allowed to access. When I'm building an authorization system I can check to see the different features that users or that type of user should have access to. By utilizing a Use Case Diagram, it allows me to take a visual approach. It also is something I can use to show non-technical stakeholders to ensure that I'm building the system in the right way.

    Sequence Diagram:
        Lastly, after the entire application has been built, UML can still play a very helpful role. For example: if I have to build in a more advanced feature or refactor something that was built awhile ago, I can use what's called a Sequence Diagram. Sequence Diagrams are able to see all of the messages the system is passing internally to ensure that I'm building my methods in an efficient way and I'm following best practices so I can implement something that'll actually work in the system.

    Package Diagram:
        After the entire system has been built, there are times where I personally go look at the code base and see how I can organize it be more efficient or I want to decrease the coupling between different modules. I may take out one part of the entire application and turn it into an outside code library. To do that, I can use a Package Diagram to see how I'm organizing the entire code base. That also gives me a very high-level overview for every component in the system and allows me to make sure that I'm conforming to best practices. If I bring a new member to the team, I can show them that Package Diagram and they'll be able to see how the entire system is organized.

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
