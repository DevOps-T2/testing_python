# testing_python
Example for perform python testing on the pipeline

## Context 
It have general 3 things in it. 

### Pytest
It shows general how to perform unit/integration test with pytest. 

### Code coverage
WIth help from pytest-cov package and a public action, it possible to specified code coverage for single files and the entire project.
To garanti that we have enough test of this project.
Source for pytest and pytest coverage, this youtube playlist helped [pytest and pytest coverage](https://www.youtube.com/playlist?list=PL0dOL8Z7pG3J6t1pqRQiNarBGY-ZnIJcq)

### SonarCloud
It integrate sonarclod, which for this public repo is free. SonarCloud testing for code smell, vulnabilities, bugs. 
It requrie a sonar_token, you can get from sonarcloud website(very easy to setup) 
For sonarCloud result, [click here](https://sonarcloud.io/dashboard?id=DevOps-T2_testing_python&branch=main)
Note, after github is finish running, it also print the linkunder sonarCloud->sonarcloud scan.
