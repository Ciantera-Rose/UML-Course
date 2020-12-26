**-Class Diagram Elements:**

    -Class Diagram Elements:
        -Three elements previously covered:
            *Name
            *Attributes
            *Operations

        -Attributes have three different items at a minimum that you should include:
            *Visibility
            *Name
            *Data Type

   -Class Diagram Associations:    
        -Association: 
            -How one class is connected to another:
            *ie.
                -Guide belongs to topic
                -Topic has many guides
                -A guide has many and belongs to tags
                -A tag has many and belongs to guides
        -Multiplicity:
            -How we designinate the direction of the relationship in regards to numbers
                -Topic: 1 Guide: 1..*    1..*     0..* Tag
        -Navigability
            -How you can take one class and have it communicate with any other classes.
            -This sets the rules for knowing how that communication can take place.
            *ie. 
                -You can find all of the guides for a topic
                -You can find all of the tags for a topic through a guide
                -You can find a guide's topic
                -You can find all tags associated with a guide
