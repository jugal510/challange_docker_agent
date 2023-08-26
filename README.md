# challange_docker_agent
Improve a Docker agent pipeline
You're an open-source developer contributing to the Hugo project, a static site generator developed using Golang.

You're using a Jenkins pipeline with a docker agent to validate your changes. However, you're finding that your pipeline is taking a long time in the build stage.

You do some research and find that your build is downloading dependencies on each run of the pipeline.

After discussing the issue with a team member, you find that you can speed up your builds by moving the dependency cache into the project workspace.

