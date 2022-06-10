# Docker

![alt_text](/images/vm-vs-container.png "vm vs container")

## Install Docker
- [Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [Manage Docker as a non-root user](https://docs.docker.com/install/linux/linux-postinstall/#manage-docker-as-a-non-root-user)

## Concept
- [Docker Tutorial - Part 1 - What is Docker, and Key Concepts](https://www.youtube.com/watch?v=T25Z4CUwYjE)
- [Virtual Machines vs Docker Containers - Dive Into Docker](https://www.youtube.com/watch?v=TvnZTi_gaNc)
- [Docker basics](https://docs.docker.com/get-started/#setup)
- [Building Docker Containers for Go Applications](https://www.callicoder.com/docker-golang-image-container-example/)
- [Intro to Docker & Linux Namespace](https://www.youtube.com/watch?v=oLZyFKMu0dk)
- [A quick introduction to Docker tags](https://medium.freecodecamp.org/an-introduction-to-docker-tags-9b5395636c2a)
- [How I filter and grep Docker containers, images, and volumes, and how you can too](https://medium.freecodecamp.org/how-i-filter-and-grep-docker-containers-images-and-volumes-and-how-you-can-too-a60e52bf7784)

## FAQs
- [Expose vs publish: Docker port commands explained simply](https://nickjanetakis.com/blog/docker-tip-59-difference-between-exposing-and-publishing-ports)
- [Docker run vs exec: deep-dive into their differences](https://www.bitcoininsider.org/article/25173/docker-run-vs-exec-deep-dive-their-differences)
- [Dockerfile COPY vs ADD: key differences and best practices](https://phoenixnap.com/kb/docker-add-vs-copy)

## Docker Hub
https://hub.docker.com/

## Docker Union FS:
- https://docs.docker.com/storage/storagedriver/aufs-driver/#how-the-aufs-storage-driver-works

## Docker OCI Image Spec:
- https://github.com/opencontainers/image-spec/blob/master/spec.md

## Docker BuildKit:
https://github.com/moby/buildkit
https://github.com/genuinetools/img
https://github.com/GoogleContainerTools/jib

## Docker PID 1:
- https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/

## CRI Variants
- https://kubernetes.io/blog/2016/12/container-runtime-interface-cri-in-kubernetes/
- https://containerd.io/ (from Docker)
- http://cri-o.io/ (from RedHat)

![containerd](/images/docker/containerd.png "containerd")

![docker-containerd-2](/images/docker/docker-containerd-2.jpeg "containerd as docker")

![cri-containerd](/images/docker/cri-containerd.png "containerd as CRI")



## RUNC variants:
- https://github.com/opencontainers/runc
- https://github.com/google/gvisor
- https://katacontainers.io/
- https://nabla-containers.github.io/
