# Helm Chart for "healthchecks"

Initial helm chart with the goal to deploy [healthchecks](https://github.com/healthchecks/healthchecks)

Installation:

```shell
helm upgrade --install healthchecks . -f my-values.yaml -n healthchecks
```

Uninstallation:

```shell
helm uninstall healthchecks -n healthchecks
```