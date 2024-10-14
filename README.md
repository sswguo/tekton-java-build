The pipeline is used to run a java build against the specific mirror.

There are two tasks in it, one is [git-clone](https://hub.tekton.dev/tekton/task/git-clone) and the other one is `build-java-project`. 

# Tasks

build-java-project: it supports to specify the mirror with parameter `mirror`, this is useful when you want to test the performance on different mirrors.

## Parameters
- url: Repository URL
- mirror: Mirror of the maven repo