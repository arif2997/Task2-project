Login to your self-hosted server.
Install gitlab-runner (Gitlab official site has the procedure)
Give the proper permission to "gitlab-runner" binary
gitlab-runner start
gitlab-runner register
Provide the gitlab URL, token from ( gitlab Settings -> CICD ).
Give the Tag(centos), executor(docker) of your runner.
Prepare the ".gitlab-ci.yml" file in your Git repo.
