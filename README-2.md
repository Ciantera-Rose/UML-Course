

    -UML Components and Common Elements:
        *Six common elements shared across various diagrams:
            -Frames
            -Classifiers
            -Stereotypes
            -Comments
            -Dependencies
            -Features (which are also called Properties)

    -UML Components: FRAMES: 
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

    -UML Components: CLASSIFIERS:
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

    -UML Components: COMMENTS and NOTES:
        -Common UML components are comments. 
        -Also called "Notes,"Ability to have descriptive markup.
        -In a rectangular box with dotted line to element
        -Communication clarity for anyone reading it
        -Explanations outside of normal scope

    -UML Components: DEPENDENCIES:
        -Denotes coupling. Gives abilty to see how badly one component needs another component
        -Dotted line with open arrow
        -Model required components 
        -Regression error prevention
        -ie. Song request class that communicates with API. Needs API to work
            *SongRequest - - - -> SpotifyAPI

    -UML Components: FEATURES and PROPERTIES:
        -Represents attributes of an element
        -Name and optional attributes
        -Implementation guidance
        -Establish standarized/strict naming convention
