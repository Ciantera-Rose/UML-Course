**Elements of a UML Activity Diagram:**

-Seven different elements:
    *Initial state or Start Point
    *Activity or Action State
    *Action Flow
    *Decisions and Branching
    *Guards
    *Final State or End Point
    *Swim Lanes

-Initial state:
    -Represented by that thick circle that has the white circle in the middle of it.
    -In an activity diagram, this is how you represent how a user or system will begin.

-Activity or Action State:
    -Significant portion of an activity diagram, each box (sometimes rounded edges) is an activity or a state. 
    -ie>
    -Generating an individual question set, confirming, and asking a question are various action states.

-Action Flow:
    -Anytime you see a filled-in arrow tip, that is an action flow. 
    -It means that we took a piece of data and took it from one action state to another action state and this action flow is how they're connected. 
    -When you confirm and ask a question, that is an action flow. 

-Decisions and Branching:
    -ie. There is a 45-degree diamond square, which is called a branch point or a decision. 
    -That represents a stage in the application where a decision has to be made. 
    -In this case, it's asking the question "was it last?" If so, it's going to perform one action, if not it's going to perform a different action. That's how you can understand branching which leads perfectly into guards.

-Guards:
    -Guards are the "no" or "yes" options. 
    -There may be times where it's more complex and have several conditions.
    -The more branches or guards that we have, the higher the level of complexity. 
    -That means if you go back to change something in that process, you're going 
     to have to populate that change throughout the entire system.


-Final State or End Point:
   -Most of the time you're going to have a final state.
   -The UML specification says that every activity diagram should have a final state.   -It's simply going to store the result inside of the system database and that's it.
   -The syntax for this is going to be an action flow from one activity to the final endpoint. 
   -It's going to have an arrow pointing to a large circle with a smaller black circle in the middle, which represents that you've come to the end of that activity.


-Swim Lanes:   
    -ie: example: 
    -A quiz that is the activity diagram, inside of that we have swim lanes.
    -A teacher, a system, and a student.
    -This represents a way of organizing each of the activities.
    -We know when a teacher should be for performing a task
    -When a system/server should be performing a task
    -When a student should be performing a task
    -This is helpful the more complex a system gets, the more actors in the
     process, you want to organize the entire system this way. At a simple glance, anyone will be able to see what the teacher can do, what the system can do, and what roles and responsibilities the student is going to have.

    