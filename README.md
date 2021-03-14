Amazon Linux Systemd Container Image
===========================

This Containerfile can build containers capable to use systemd.

[![amazonlinux build status](https://quay.io/repository/ucomesdag/amazonlinux/status "Container Repository on Quay")](https://quay.io/repository/ucomesdag/amazonlinux)

Branches
--------

This repository has multiple branches that relate to amazonlinux versions.

|Branch |Amazon Linux Version|Container image tag|
|-------|--------------------|-------------------|
|main   |2                   |latest             |

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
  quay.io/ucomesdag/amazonlinux
```
