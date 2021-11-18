# MATLABTest: Integrating MATLAB workflows with Github Classroom through Python unit testing
## Overview
Through this example workflow, the aim is to illustrate how MATLAB can be integrated with Github Classroom. Previously, examples have focused on the integration of Python due to the fact that MATLAB is licensed and therefore cannot be executed on Github.

Examples in this workflow can be extended to other languages that are supported by Github, e.g. R, Python, C, C++, Java and theoretically any language that can be called through Python (which will be our main source of unit testing).

## What is unit testing?
Unit testing allows for instantaneous feedback on code, by providing tests to check that the output of a student's script matches the expected output that the facilitator sets. This is extremely useful, particularly when students are first learning a topic or language. Instant feedback will increase students' confidence in their own work (cite). Finally, Github offers functionality to comment on code style; that is, ensuring that students follow good coding practice. Areas that can be improved will be highlighted - examples include indentation, commenting and variable names.

## How does this all work?
The facilitator sets up an online Github repository, just like this. Whenever someone signs up to their classroom either through a link to sign up or through SSO, a copy of the repository is made for the individual that the facilitator can also access. The facilitator can set up a file for them to edit/correct, which the tests will check and provide feedback for. The tests are written by the facilitator, and in this example will be in Python.

# Part 1: Editing and correcting a script
