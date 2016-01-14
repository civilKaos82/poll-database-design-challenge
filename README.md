# Design a Poll Database Schema 
 
## Summary
We've been contacted by a company that allows users to create and answer one-question polls.  The company would like us to design a database to support its business.  Below is a description of how the polls operate and a list of questions which our schema design should support answering.


### Description of Polling
When users create a new poll, they supply one question that will be presented to poll takers.  They also supply a list of response options from which poll takers select their answers.  When users take a poll, they are presented with the poll question and the list of response options.  The poll takers select a response option.  Poll creators can then review the responses to their polls.

For example, a poll might pose the question "Which is your favorite Ruby programming book?" and offer the response options *The Well-grounded Rubyist*, *Eloquent Ruby*, and *Practical Object-oriented Design in Ruby*.  Users taking the poll would select one of the provided options.  


### Questions to Answer
For a user,
- which polls did the user create?
- which polls did a user take?
- which response option did a user select for a poll?

For a poll,
- which user created the poll?
- which users have taken the poll?
- what question does the poll present to takers?
- what are the possible responses to the poll?
- what response options have takers made to the questions?

For a response option,
- for which poll was the response option written?
- which users have selected the response option?


## Releases
### Release 0: Design a Schema to Support Polling
Design a database schema to support the polling described in the *Summary*.  Each of the questions in presented in the *Summary* should be answerable based on our schema design.
 
Use [SQL Designer][] to create a visual representation of the schema.  When we're done, [take a screenshot][mac screenshot instructions] of the final schema design.  Add the screenshot image to the challenge directory and use git to commit the change.


## Conclusion
This challenge presented us with another opportunity to design a database schema to support an application.  We'll be required to do a lot of database design moving forward at Dev Bootcamp.  Take time with pairs, fellow Boots, and instructors to clear up any lingering questions related to schema design.


[mac screenshot instructions]: https://support.apple.com/en-us/HT201361
[SQL Designer]: https://schemadesigner.devbootcamp.com/
