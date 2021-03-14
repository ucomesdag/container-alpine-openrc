Docker Alpine openrc
====================

This Dockerfile can build containers capable to use openrc.

[![centos build status]((https://quay.io/repository/mesdag/alpine/status "Docker Repository on Quay")](https://quay.io/repository/mesdag/alpine)

Branches
--------

This repository has multiple branches that relate to Alpine versions.

|Branch |Alpine Version|Docker image tag|
|-------|--------------|----------------|
|master |3             |3               |
|edge   |edge          |edge            |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  quay.io/mesdag/alpine
```
