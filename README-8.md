    **Elements of a UML Deployment Diagram**

        -Deployment Diagrams: Deciding the architecture for a system

        -Six elements make up a deployment diagram;
            *Nodes
            *Components
            *Artifacts
            *Links
            *Dependencies
            *Associations

        -Nodes:
            -One of the most important parts of the system.
            -Essentially, every component of a deployment diagram is a node.
            -Everything else is simply adding detail to that node or it's showing how 
             the nodes are related to each other.
            -The node itself is the actual real world component.

        -Components:
            -May have differnt  syntax options.
            -A component could be an application, a web service, the API itself or 
             a database, there are numerous things a component could be. 
            -Usually, it is the actual piece of software that manages
             communication  and handles the business logic for the node that it resides on.

        -Artifacts:
            -Items that are surrounded by angle brackets.
            -What type of server you want to deploy.
            -What type of application you want to configure.
            -Descriptive and tells architect how everything needs to be configured.

        -Links:
            -The links are those lines that are connecting each one of the nodes.
            -ie. link from the angular front end to the authentication system. 
            -ie. link between the front end and the rails API.
            -ie.a link between the API and the authentication system.
            - That's a way of showing how each one of the nodes is connected.


        -Dependencies:
            -Use when you want to be more specific than links.
            -Represented by dotted line with arrows going in the direction of the node.
            -It shows what other nodes it depends on and will not function properly  
             without them.

        -Associations:
            -Similar to links and dependencies.
            -It's a way of connecting all the nodes and showing how they're associated.
            -You will have to set up a number of items that this deployment. 
             diagram essentially gives you a recipe for.