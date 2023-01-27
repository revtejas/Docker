## Objectives
- What is Docker?
- What is container?
- Relation?
- How does it compare with virtual machines?

We isolate our services to make sure our services dont interfere with each other and make use of high performance, availability and security.
- To host our apps we need infrastructure
- We use VMs/ Cloud computing to setup infra
- We isolate our service in OS of VM
- Because of isolation we end up setting up multiple VMs and instances.
- VMs will be overprovisioned.
- Results in high capEx and OpEx.

Points to be noted:
- Isolating services are important ( Need OS)
- High availability avhieved by multiple VMs
- Portability matters or Eases the Deployment( images can replace VMs)
- All this raises CapEx and OpEx

Isolation without OS, But how?
VMs without Operating system but has processes running, called containers.

Containers: Process running in a Directory.

If we can create boundaries between processes, this means we are containerzing the processes and we are isolating the processes.
All the binaries, libraries and configuration for a process is isolated and available in its directory.

## Definition of Container
- Container is a kernel trick, the processes will be running on the same OS but will be isolated. 
- Container shares the machine's OS system kernel and do not require an OS per application.
- Container is a standard unit of software that packages up code and dependencies.

## Defintion of Hypervisor
- It will let you create or run virtual machines.

## VM vs Container
- Containers offer isolation not virtualization
- Containers are OS virtualization
- VMs are hardware virtualization
- VM need OS but containers dont need OS
- Containers uses host opertaing system.

# Defintion of Docker
- Docker(aka container run time environment) manages container using Docker Engine.
- 
