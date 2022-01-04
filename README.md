# Gradle issue reproducer

This is a template repository to create reproducer projects for Gradle issues.
The template contains a GitHub Action definition that runs a Gradle build upon each code change.
To quickly learn how it works check the following screencast:

https://user-images.githubusercontent.com/419883/147940456-d0c96c90-f2b5-4574-8133-09647db9545a.mov

## How to use the template

- Fork this repository
  - On the main page click the `Use this Template` button
  - Specify the user/org name and a repository name
  - Select `Public` for repository type
  - Select `Include all branches`
  - Click `Create Repository from template`
- Modify the project in the repository to reproduce the issue
  - You can clone your new forked repository locally and push changes, as usual
  - You can also edit your reprocer in an online editor by replacing `github.com` with `github.dev` in the URL (or by pressing the '.' key on the keyboard).
- Adjust the [GitHub Action file](.github/workflows/run-reproducer.yml)
  - You can configure the executed Gradle tasks as well as the environment (JVM version, operating system, etc.)
  - The documentation for the Gradle GitHub Action is available [here](https://github.com/gradle/gradle-build-action)
- Verify that the reproducer exhibits the problem on the [GitHub Action page](https://github.com/gradle/gradle-issue-reproducer/actions)
- Link your reproducer to the issue
