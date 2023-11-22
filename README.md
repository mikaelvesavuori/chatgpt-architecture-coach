# Collection of ChatGPT (or other LLM) priming prompts for software architecture

This is my collection of helpful priming prompts for ChatGPT, or other LLMs, when discussing various angles of software development and architecture.

## Cloud architecture coach

This is targetted as a "living dialogue" with heavier interaction between both parties. You'll get lots of follow-up proposals and diagrams and code examples.

### Example input

```md
We are struggling with understanding how to apply the "branching by abstraction" notion to our serverless functions. Currently, we have lots of integration issues and have no API versioning. We want to use this pattern to evolve and increase the stability.
```

## Assess diagram

This is a great way to get feedback on a digitally-generated diagram.

_You will have to use an LLM that can take image input._

## Code review with policy

For a cheap, fast, helpful code review, you can use an LLM. Even better, set it up with your own policy of things you care about!

## Generate diagram from drawing (whiteboard or sketch)

It's common to draw architecture diagrams on paper or on a whiteboard. Let the LLM do the majority of work by converting your drawing into a formal, digital diagram.

Make sure to explain the context well, and to draw cleanly.

_You will have to use an LLM that can take image input._

## Software delivery performance coach

Here we are expecting a discussion around specific performance issues in our team, using DORA data or (if modified) our overall issues. This will address both cultural and technical issues.

### Example input

```md
Our current DORA metrics (spanning a 30 day period) are:

- Change failure rate: 3%
- Deployment frequency: 3.12 per day
- Lead time for changes: 7 minutes
- Mean time to recover: 104 minutes
```

## Technical debt analysis

This one is all about getting concrete advice on problems a formal analysis has uncovered. It will prioritize and explain why certain activities should get more attention than other. It also helps with adapting the language to non-technical users.

### Example input

Run a [HealthCheck review](https://docs.google.com/spreadsheets/d/18uoetVewKqLgwOBw8l256eT0aLIFoJyWdo2IE_ZbAHg/copy) and export the results as CSV. This won't be 100% exact when using with ChatGPT due to the structure of the document but it should be able to give you a good start.

## Integration tests from API schema

To scaffold your integration test suite, just ask the LLM to setup the critical tests based on your API schema.
