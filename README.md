# RPM and container testing

1) Install [task](https://taskfile.dev/installation/)
2) Run `task -t taskfiles/build.yml` to build the container and .devcontainer file
3) Make sure you have the MS devcontainers extension installed
3) Reopen the workspace in the container CTRL-SHIFT-P -> Reopen in container   
4) Run `task -t taskfiles/test.yml` to test the container in the container.


Please take note of the taks descirptions and summarizes. Although of the tasks pass, 
some are negative tests showing an issue.