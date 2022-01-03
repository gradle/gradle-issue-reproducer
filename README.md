# Gradle issue reproducer

This is template repository to supply reproducer projects for issues reported in the Gradle issue tracker.

## How to use the template

- Clone this repository
- Modify the project in the repository to reproduce the issue
- Adjust the [Gradle GitHub Action](.github/workflows/run-reproducer.yml) in the `.github/workflows` folder according to the reproducer (tasks to execute, JVM version, Operating system, etc)
  - The documentation for the Gradle GitHub Action is available [here](https://github.com/gradle/gradle-build-action).
- Verify that the reproducer exhibits the problem on the [GitHub Action page](https://github.com/gradle/gradle-issue-reproducer/actions)
- Link your reproducer repository to the to the issue

## Screencast
https://user-images.githubusercontent.com/419883/147940456-d0c96c90-f2b5-4574-8133-09647db9545a.mov

