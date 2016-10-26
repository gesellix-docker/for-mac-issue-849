
reproduce the issue at https://github.com/docker/for-mac/issues/849 by:

    docker run --rm -it -v /var/run/docker.sock:/var/run/docker.sock gesellix/for-mac-issue-849 ./gradlew integrationTest --tests "*DockerSwarmIntegrationSpec"

