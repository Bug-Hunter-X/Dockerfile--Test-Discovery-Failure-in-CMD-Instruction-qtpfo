# Dockerfile Bug: Test Discovery Failure

This repository demonstrates a common error in Dockerfiles related to running unit tests. The provided `Dockerfile` attempts to run tests using `python3 -m unittest discover`, but fails because it doesn't specify the test directory correctly or handle potential issues with the unittest discovery mechanism.

The `Dockerfile_solution.txt` file shows how to fix this to run unit tests successfully within a Docker container. 

This is particularly relevant when you are using frameworks like `unittest` or `pytest` inside your docker image.