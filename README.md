# my-project
learning to use github action for ci/cd with techword with nana

NOTE: CI/CD is only ONE OF the many workflows that could be written in a developer environment. - it involves the automation of the building, testing and deployment of a written application and consequent push request changes.

1. clone nana's Java App with Gradle
2. build docker image 
3. push to private docker repository

using github actions - one could pick a workflow template

*it is important for a ci tool to be able to integrate with different other tools. because different technologies require a combination of so much varying other tools.


name

jobs
    uses -> selects an action (whenever we are dealing with something in the repository.)
    with -> 
    run -> this command is used to write a command-line command