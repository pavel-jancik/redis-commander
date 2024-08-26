# Redis-commander helm chart repo
This is unofficial helm repository with helm chart for redis-commander.

For helm chart sources see [main](https://github.com/pavel-jancik/redis-commander/tree/master) branch and [releases](https://github.com/pavel-jancik/redis-commander/releases).


To get the redis-commander helm chart run:
```sh
helm repo add redis-commander https://raw.githubusercontent.com/pavel-jancik/redis-commander/helm-repo/
# "redis-commander" has been added to your repositories

helm repo update redis-commander
# Hang tight while we grab the latest from your chart repositories...
# ...Successfully got an update from the "redis-commander" chart repository
# Update Complete. ⎈Happy Helming!⎈


# List charts in the repo
helm search repo redis-commander
# NAME                            CHART VERSION   APP VERSION     DESCRIPTION
# redis-commander/redis-commander 0.6.0           latest           A Helm chart for redis-commander
```
