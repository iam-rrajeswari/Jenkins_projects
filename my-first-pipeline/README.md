# A simple jenkins pipeline to verify if the docker slave configuration is working as expected.


Docker container with the image node:16-alpine is used as the agent. This provides a consistent and isolated environment for the pipeline execution.

This pipeline script sets up a Docker container with Node.js 16-alpine as the execution environment. It then defines a single stage named "Test" that simply prints the Node.js version. This is a basic example, and real-world pipelines often involve multiple stages, complex scripts, and integrations with other tools.
