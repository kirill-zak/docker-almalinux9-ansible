# AlmaLinux 9 Ansible test image
AlmaLinux 9 docker container for Ansible playbook and role testing.

## Tags

  - `latest`: Latest stable version of Ansible

## How to Build

To build the image on your own locally, do the following:

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. `cd` into this directory.
  3. Run `docker build -t docker-almalinux9-ansible .`


## How to Use

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. Build image via `docker build -t docker-almalinux9-ansible .`
  3. Run a container from the image: `docker run --detach --privileged --volume /sys/fs/cgroup:/sys/fs/cgroup:ro --volume /var/lib/docker/aufs:/var/lib/docker/aufs/ docker-almalinux9-ansible:latest`

## Author

[Kirill Ziuzin](https://kirill-zak.ru/)

## Thanks

Based on ideas of [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).