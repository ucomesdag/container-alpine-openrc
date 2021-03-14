Alpine OpenRC Container Image
====================

This Containerfile can build containers capable to use openrc.

[![alpine build status](https://quay.io/repository/ucomesdag/alpine/status "Container Repository on Quay")](https://quay.io/repository/ucomesdag/alpine)

Branches
--------

This repository has multiple branches that relate to Alpine versions.

|Branch |Alpine Version|Container image tag|
|-------|--------------|-------------------|
|main   |3             |3                  |
|edge   |edge          |edge               |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
podman run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  quay.io/ucomesdag/alpine
```
