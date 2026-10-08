# Devcontainer Workflow
I am testing out the [Devcontainers](https://github.com/devcontainers/cli).

## Setup
``` bash
# Install the CLI (if not already installed)
npm install -g @devcontainers/cli

# Build and open the project in a container
devcontainer up --workspace-folder .

# After making changes to .devcontainer, rebuild
devcontainer build

# Once the container is running:
# pnpm dev
# As of right now this doesnt work right out of the box. the best thing to do is use VS Code to start the container
```
