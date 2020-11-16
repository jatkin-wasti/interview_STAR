# This document contains answers for common interview questions in STAR format
## What is STAR?
- Situation: Provide context of the task
- Task: Describe what the task actually was
- Action: Explain what you did to meet the challenge
- Result: Review what happened because of your actions
## Agile
**What is Agile?**
- Agile is a methodology that allows for rapid delivery of increments throughout the development of a product
. Therefore allowing for frequent internal and external feedback to guide the process.
- S: During my training with Sparta Global we were often set small tasks to be completed individually
- T: One such task was writing a short Elevator's Pitch to sell ourselves to clients
- A: I completed this and then performed my pitch to the rest of the class to get rapid feedback on
 my work
- R: This meant that I could improve my pitch based on feedback as early as possible, leading to a more engaging
 iteration that would successfully highlight my strengths.

**What are the agile values?**
- The agile values are a set of priorities that should be understood in an agile environment. They are prioritising
 individuals and interactions over processes and tools, working software over comprehensive documentation, customer
  collaboration over contract negotiation, and responding to change over following a plan. 

**What are the agile principles?**
- The agile principles are a set of guiding principles that help to easily identify an Agile environment and hold
 your project to the Agile mark. 

**Agile vs V model vs Waterfall**
- Waterfall: Series of linear sequential phases where each phase relies on the previous phase. This isn't very
 flexible or iterative as progress flows down the model. Useful to keep up momentum on a project if employees leave
, as their understanding and knowledge is preserved in the thorough documentation required. Can be suitable in
  fields where requirements and technology are fixed and unlikely to change.
- V model: Linear phases that are linked to a corresponding test phase. Verification occurs against the
 requirements and validation occurs against the user needs. This helps to avoid the downward flow of defects. Can be
  used in smaller projects that have clearly defined requirements.
- Agile: Linear phases in a continuous improvement cycle where each cycle is much shorter than in other models. Can
 be used in areas where change is expected or on new projects with a suitable team. 

**What are user and epic stories?**
- User stories are a series of low level requirements or requests from a user's perspective that can be completed in
 a sprint. Format is "As a [type of user], I want to [action] so that [outcome]."
- An Epic story is a large body of work that is much larger in scope and covers high level functional and non-functional
 (technical) requirements from a business user's perspective.
 
### Scrum
**What is the difference between Agile and Scrum?**
- While Agile is a methodology or philosophy, Scrum is a specific framework that can be implemented to manage a
 project in an Agile way.
- S: At Sparta Global we had a lot of work to cover each week in our training
- T: We had to organise ourselves as a team in a way to effectively communicate our goals for the week and what needed
  to be accomplished
- A: We utilised the Scrum framework by having daily standups where we discussed what we were going to achieve in each
  sprint
- R: Everyone was well informed about what was required of them and how long we had to complete each task which
 reduced misunderstandings and stress
 
**What are the 3 amigos?**
- 3 perspectives to consider when examining an increment of work so that everyone is on the same page, eliminating
 areas of confusion and misunderstanding early on
- Business: Expectations from user stories
- Development: Understanding of requirements and the length of time required to complete that increment
- Testing: Finding edge cases and thinking about how the test cases match up with the outlined acceptance criteria

**What is a Scrum persona?**
- Persona's are detailed fictional characters that can be created to identify the needs of the target user base and
 gain an understanding of which features are important and why

**What are information radiators?**
- Objects displaying information about a project in a clearly visible location for both the team and others to easily
 keep up to date. This helps start conversations and fosters team responsibility.

**What are Scrum artifacts?**
- Product backlog: Ever evolving list of features needed for a product
- Sprint backlog: List of objectives to complete during this sprint
- Burndown charts- Graphical representation of remaining work in a given sprint. Updated during daily scrums

**What are Scrum roles?**
- Scrum Master: Upholds Agile Values and makes sure that everyone involved can do what they need to do
- Product Owner: Understands customer needs to be able to manage the scrum backlog
- Development Team: The people doing the work to complete the sprint goals

**What are Scrum ceremonies/events?**
- Sprint Planning: Deciding what to tackle this sprint. Takes no more hours than double the sprint length in weeks e.g. 2 hours for a 1 week sprint.
- Daily Scrum: Short standup meeting to get everyone on the same page. What are the team tackling that day, and updating everyone on what happened since the last meeting. Usually less than 15 minutes.
- Sprint Review: Meeting where the team demo what they've accomplished in the sprint. One hour per sprint week e.g. 3 hour sprint review for a 3 week sprint.
- Sprint Retrospective: Identifying what went well and what problems arose for that sprint, and how that knowledge can be used going forward. Last no more than 1.5 hours for a 2 week sprint.

**What is a starfish retrospective?**
- ALlows the team to consider their current approach and what could be done differently
- What to start doing?
- What to stop doing?
- What to continue doing?
- What to do more of?
- What to do less of?

**What is root cause analysis?**
- Methodology of analysing problems to find the main or root cause of that problem. Golden rule for this is to ask
 why (often this is 5 times) until you get to the underlying cause of the issues so that you know what actions you
  can take next time.
## SQL
**What is a foreign key?**
- A foreign key is a primary key from another table that is used in the many side of a table relationship

**What are many to many relationships and how do we handle them?**
- When multiple instances of table A correspond to multiple instances of table B e.g. an author can write multiple
 books, and each book can be written by multiple authors.
- S: Creating a relational database for a library
- T: This involved normalising the database and resolving the M:N relatioship between Authors and Books
- A: I created a linking table between them which contained foreign keys from both tables
- R: This made the design more efficient and flexible as there are less potentially unused columns and I didn't have to
 impose artificial restrictions on the database

**What is DML?**
- Data Manipulation Language: SELECT, INSERT, UPDATE, DELETE

**What is DDL?**
- Data Definition Language: CREATE ALTER, DROP, TRUNCATE
 

## Python
**What are the four pillars of OOP?**
- Abstraction: Reduces complexity by showing only what's necessary of an object to other parts of your program, and
 isolates impact of changes
- Encapsulation: Reduces access and increases reusability by wrapping up data (class variables) and functionality
 (methods) together into a single place
- Inheritance: Eliminates redundant code as an object can acquire the properties of another (super) object. Allowing
 us to reuse, customise and enhance existing code
- Polymorphism: Refactor code to process objects differently depending on their data type 
or class
- S: In my dissertation I created a simulation of the effects that different agricultural practices had on the
 nutrient levels in soil
- T: I chose Java for this, and had to create multiple crops with differing nutrient requirements
- A: I utilised the OOP aspects of Java to create a crop class that contained all of the functionality and data for a
 crop, having each crop be an instance of that, or a child class, that can be initialised with different values 
- R: This ensured my software adhered to the DRY principle as this shared functionality was encapsulated in the Crop
 class and that specific crops could inherit these attributes and build off them as needed

**What is TDD?**
- S: During my training with Sparta, I had to design a calculator program
- T: This had to be well tested and reliably give accurate results
- A: I utilised TDD to design tests with expected values, unexpected values and edge cases 
- R: This gave me a good idea of what I needed to keep in mind while designing the calculator's functionality and
 resulted in a robust program that successfully met all of the user's requirements

## DevOps
**What is DevOps and why should we use it?**
- Breaks down silos between the Development team and the Operations team, leading to less friction and more
 productive collaboration to massively increase efficiency
- Uses CI/CD pipeline to provide quality updates to meet customer needs as quickly as possible
- Utilises version control to easily identify problems when changes are made and always have stable versions to fall
 back on

**What is CI/CD**
- CI/CD is the backbone of DevOps operations
- Continuous Integration: Frequently (many times a day) integrating the developers work together
- Continuous Delivery: Producing software and testing it in short cycles so that it can be released manually whenever
 it is needed
- Continuous Deployment: Similar to Continuous Delivery but with regular automated deployments of the produced software
