This exercise is about a hypothetical situation where we have a **python** application being worked on by a team of about 6 people.  

## Linting
Linting process involves running a program called Linter to analyse code for potential errors and to maintain formatting standards across the project. A program called [ruff](https://docs.astral.sh/ruff/) can be used to check if a Python code conforms to the linting rules specified in a config file. The team can discuss the rules for formatting to ensure all the project code is formatted according to an agreed upon standard.

## Building/Testing
Since Python is an interpreted language, checking its build mainly revolves around testing its execution. GitHub Actions offers a [python workflor](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python) to build, test and publish a Python application.

## Alternatives for Jenkins and GitHub Actions
The most common service that comes up when searching for alternative CI/CD pipelines is GitLab. It seems relatively easy to configure just like GitHub.

Travis CI is another similar offering for CI/CD integration which can be integrated with various git solutions such as GitHub, GitLab, bitbucket etc.

## Self-hosted or cloud-based?
If the application doesn't have any specific feature requirements for the CI/CD pipeline, I would go for a cloud-based environment because its simplicity will allow the team to focus more on coding the application than configuring the CI/CD system. 
