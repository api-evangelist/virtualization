# Virtualization (virtualization)
An index and topic collection covering virtualization across two intertwined domains: machine virtualization (hypervisors, virtual machines, VDI, and cloud VM platforms) and API/service virtualization (mock servers, service mocks, and contract-based stubs). Machine virtualization abstracts physical hardware so multiple isolated operating systems can run on shared infrastructure, while API virtualization simulates the behavior of real APIs and services so teams can develop, test, and demo against realistic endpoints without depending on live production systems. This collection brings together hypervisors and VM platforms like VMware, Hyper-V, KVM, Xen, Proxmox, Nutanix, and KubeVirt; cloud VM offerings from AWS, Azure, Google Cloud, DigitalOcean, Linode, Hetzner, Scaleway, and OVHcloud; and API/service virtualization tools like WireMock, Microcks, Hoverfly, MockServer, Mockoon, Prism, Beeceptor, Pact, Specmatic, ReadyAPI, and Speedscale.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Virtualization, VM, Hypervisor, API Virtualization, Service Virtualization, Mock Server, VDI

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Virtual Machine Schema](https://raw.githubusercontent.com/api-evangelist/virtualization/refs/heads/main/json-schema/virtualization-virtual-machine-schema.json)
- [JSONSchema - Mock Endpoint Schema](https://raw.githubusercontent.com/api-evangelist/virtualization/refs/heads/main/json-schema/virtualization-mock-endpoint-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/virtualization/refs/heads/main/json-ld/virtualization-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/virtualization/refs/heads/main/vocabulary/virtualization-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Hypervisors and Virtual Machine Platforms | Type-1 and type-2 hypervisors (VMware vSphere/ESXi, Microsoft Hyper-V, KVM, Xen, Proxmox VE, Nutanix AHV, Citrix Hypervisor) abstract physical hardware so multiple isolated guest operating systems can share compute, memory, and storage. |
| Cloud Virtual Machines | Cloud providers expose VM-as-a-service offerings (Amazon EC2, Azure Virtual Machines, Google Compute Engine, DigitalOcean Droplets, Linode, Hetzner, Scaleway, OVHcloud) that programmatically provision, scale, and manage VMs across regions and instance types. |
| VM Images and Templates | Image and template tooling (EC2 Image Builder, Vagrant boxes, OVAs, AMIs, Proxmox templates) capture reproducible OS and application baselines that can be launched as new VMs on demand. |
| Lightweight and Container-Native Virtualization | Modern microVM and container-native virtualization platforms (Firecracker, KubeVirt, Lima) deliver VM isolation with container-like density and startup times for serverless, multi-tenant, and developer workloads. |
| API and Service Virtualization | API virtualization tools (WireMock, Microcks, Hoverfly, MockServer, Mockoon, Prism, Beeceptor) simulate the behavior of real HTTP, REST, gRPC, and message-based services so teams can develop, test, and demo against realistic endpoints without live dependencies. |
| Contract Testing and Mocking from OpenAPI | Contract-based virtualization (Pact stubs, Specmatic, Prism, Microcks, Postman Mock Server) generates mocks directly from OpenAPI, AsyncAPI, GraphQL, and Pact contracts to validate consumer/provider behavior throughout the SDLC. |
| Performance and Traffic Replay | Tools like Speedscale and Hoverfly capture and replay real production traffic against virtualized services for load testing, regression testing, and resilience engineering. |

## Use Cases

| Name | Description |
|------|-------------|
| Infrastructure Consolidation and Server Virtualization | Enterprises consolidate physical servers onto VMware vSphere, Hyper-V, or Proxmox clusters to improve hardware utilization, simplify operations, and enable live migration of workloads. |
| Self-Service Cloud VM Provisioning | Platform teams expose Amazon EC2, Azure VMs, or Google Compute Engine through internal portals and APIs so developers can spin up VMs on demand without raising tickets. |
| Local Development Environments with Vagrant and Lima | Developers use Vagrant, Lima, and similar tools to reproducibly build local VM-based environments that match production OS, runtime, and dependency baselines. |
| Parallel Front-End and Back-End Development | Front-end and back-end teams use WireMock, Mockoon, or Postman Mock Server to virtualize APIs from OpenAPI contracts so UI work can proceed before the real backend is implemented. |
| Integration Testing Against Third-Party APIs | QA teams virtualize third-party APIs (payments, identity, shipping) with Microcks, MockServer, or Hoverfly to run integration tests deterministically without hitting rate limits or burning real money. |
| Demos and Sales Engineering Environments | Sales engineers and partners use API mocks and lightweight VMs to spin up disposable demo environments that look and behave like production without exposing real customer data. |
| Disaster Recovery and VM Migration | Operators use VMware, Nutanix, and OpenStack tooling to snapshot, replicate, and migrate VMs across sites for DR drills, datacenter exits, and cloud migrations. |

## Integrations

| Name | Description |
|------|-------------|
| VMware | Enterprise virtualization platform spanning vSphere, ESXi, NSX, and vCenter for managing VMs, networking, and storage across private and hybrid clouds. |
| Amazon EC2 | AWS elastic compute service providing on-demand virtual machines across hundreds of instance types, AMIs, and regions through a programmable API. |
| Azure Virtual Machines | Microsoft Azure's IaaS VM offering with Linux and Windows images, scale sets, spot instances, and tight integration with Azure networking and identity. |
| Google Cloud Compute Engine | Google Cloud's VM service offering custom machine types, live migration, sole-tenant nodes, and confidential VMs. |
| Proxmox VE | Open-source virtualization platform combining KVM hypervisor and LXC containers with a unified web UI and REST API for self-hosted clouds. |
| Nutanix | Hyperconverged infrastructure platform with the AHV hypervisor that unifies compute, storage, and networking for private and hybrid clouds. |
| WireMock | Open-source API mocking and service virtualization tool for HTTP services, widely used in CI pipelines and contract testing. |
| Microcks | CNCF Sandbox API mocking and contract testing platform that turns OpenAPI, AsyncAPI, gRPC, and Postman collections into deployable mocks. |
| Hoverfly | API simulation and service virtualization tool that captures and replays HTTP/HTTPS traffic for testing and development. |
| MockServer | Flexible mock server for HTTP and HTTPS that can match requests, return canned responses, and verify expectations across multiple languages. |
| Mockoon | Desktop and CLI tool for designing and running local API mocks from OpenAPI specs without writing code. |
| Prism | Stoplight's open-source HTTP mock server and contract validator that runs OpenAPI 3 specs as live mock APIs. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [Virtual Machine Schema](json-schema/virtualization-virtual-machine-schema.json)
- [Mock Endpoint Schema](json-schema/virtualization-mock-endpoint-schema.json)

### JSON Structure

- [Virtual Machine Structure](json-structure/virtualization-virtual-machine-structure.json)
- [Mock Endpoint Structure](json-structure/virtualization-mock-endpoint-structure.json)

### JSON-LD

- [Virtualization Context](json-ld/virtualization-context.jsonld)

## Vocabulary

- [Virtualization Vocabulary](vocabulary/virtualization-vocabulary.yaml) — Unified taxonomy spanning hypervisor and cloud VM platforms alongside API/service virtualization tooling, mapping resources, actions, workflows, and personas across both domains.

## Network

This index references the following virtualization repositories:

- [Amazon EC2](https://github.com/api-evangelist/amazon-ec2)
- [Amazon EC2 Auto Scaling](https://github.com/api-evangelist/amazon-ec2-auto-scaling)
- [Amazon EC2 Image Builder](https://github.com/api-evangelist/amazon-ec2-image-builder)
- [Amazon Lightsail](https://github.com/api-evangelist/amazon-lightsail)
- [Azure Virtual Machines](https://github.com/api-evangelist/microsoft-azure-virtual-machines)
- [Beeceptor](https://github.com/api-evangelist/beeceptor)
- [Broadcom](https://github.com/api-evangelist/broadcom)
- [Citrix](https://github.com/api-evangelist/citrix)
- [Digital Ocean](https://github.com/api-evangelist/digital-ocean)
- [Firecracker](https://github.com/api-evangelist/firecracker)
- [Google Cloud Compute Engine](https://github.com/api-evangelist/google-cloud-compute-engine)
- [Google Cloud VMware Engine](https://github.com/api-evangelist/google-cloud-vmware-engine)
- [Hetzner](https://github.com/api-evangelist/hetzner)
- [Hoverfly](https://github.com/api-evangelist/hoverfly)
- [KubeVirt](https://github.com/api-evangelist/kubevirt)
- [Lima](https://github.com/api-evangelist/lima)
- [Linode](https://github.com/api-evangelist/linode)
- [Microcks](https://github.com/api-evangelist/microcks)
- [Mock Service Worker](https://github.com/api-evangelist/mock-service-worker)
- [mockAPI](https://github.com/api-evangelist/mockapi)
- [Mockoon](https://github.com/api-evangelist/mockoon)
- [MockServer](https://github.com/api-evangelist/mockserver)
- [Nutanix](https://github.com/api-evangelist/nutanix)
- [OpenStack](https://github.com/api-evangelist/openstack)
- [OVH Cloud](https://github.com/api-evangelist/ovh-cloud)
- [Pact](https://github.com/api-evangelist/pact)
- [Postman](https://github.com/api-evangelist/postman)
- [Prism](https://github.com/api-evangelist/prism)
- [Proxmox VE](https://github.com/api-evangelist/proxmox)
- [ReadyAPI](https://github.com/api-evangelist/readyapi)
- [Scaleway](https://github.com/api-evangelist/scaleway)
- [SmartBear](https://github.com/api-evangelist/smartbear)
- [Specmatic](https://github.com/api-evangelist/specmatic)
- [Speedscale](https://github.com/api-evangelist/speedscale)
- [Stoplight](https://github.com/api-evangelist/stoplight)
- [Vagrant](https://github.com/api-evangelist/vagrant)
- [VMware](https://github.com/api-evangelist/vmware)
- [VMware Tanzu](https://github.com/api-evangelist/vmware-tanzu)
- [WireMock](https://github.com/api-evangelist/wiremock)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
