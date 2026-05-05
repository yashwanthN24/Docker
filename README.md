# Docker

- Docker is a containerization tools used to run multiple containers from Dockerfiles
- Virtual Machines Provide complete isolation from each other but they are larger in size
- A normal Ubuntu image iso file is over 3GB
- And snapshots created from Virtual Machines are in the size of GB's so sharing and collaboration is expensive
- Containers Solve this exact problem they dont not contain a full OS like VM's they make use of the host
  operating system resources.
- A Container = App + Its Dependencies + System Dependencies (Required to run your app)
- So hence a Container is lightweight and easy for modern collaboration and deployments especially with the modern
  microservices architecture


- Containerization Tools : Docker , Podman , Builtdaa

**Problems with Docker**

- Docker runs on a single host process called docker daemon (Making it a single point of failure/concern)
- Docker daemon is responsible for spinning up the container , building images etc it acts as a Container engine

- Podman and Builtdaa containerization tools solve this problem

