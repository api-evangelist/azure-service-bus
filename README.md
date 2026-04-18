# Azure Service Bus (azure-service-bus)
Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics, providing reliable message delivery for decoupling applications and services in cloud and hybrid environments.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure-service-bus/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Azure, Cloud, Enterprise, Message Broker, Messaging, Pub/Sub, Queues

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-18

## APIs

### Azure Service Bus
Azure Service Bus is a fully managed enterprise message broker supporting message queues and publish-subscribe topics with features like dead-lettering, sessions, scheduled delivery, and transactions for building reliable distributed applications.

**Human URL:** [https://azure.microsoft.com/en-us/products/service-bus](https://azure.microsoft.com/en-us/products/service-bus)

#### Tags:

 - Azure, Cloud, Enterprise, Message Broker, Messaging, Pub/Sub, Queues

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/azure-service-bus/refs/heads/main/openapi/azure-service-bus-openapi.yml)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/azure-service-bus/refs/heads/main/asyncapi/azure-service-bus-asyncapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/azure-service-bus/refs/heads/main/json-schema/azure-service-bus-queue.yml)
- [JSONLD](https://raw.githubusercontent.com/api-evangelist/azure-service-bus/refs/heads/main/json-ld/azure-service-bus-context.jsonld)

## Common Properties

- [Portal](https://azure.microsoft.com/en-us/products/service-bus)
- [Documentation](https://learn.microsoft.com/en-us/azure/service-bus-messaging/)
- [GettingStarted](https://learn.microsoft.com/en-us/azure/service-bus-messaging/service-bus-quickstart-portal)
- [Pricing](https://azure.microsoft.com/en-us/pricing/details/service-bus/)
- [GitHubRepository](https://github.com/Azure/azure-sdk-for-net/tree/main/sdk/servicebus)
- [Blog](https://azure.microsoft.com/en-us/blog/)

## Features

| Name | Description |
|------|-------------|
| Message Queues | Point-to-point messaging with FIFO delivery, sessions, dead-lettering, and duplicate detection for reliable asynchronous communication. |
| Publish-Subscribe Topics | One-to-many messaging with topic subscriptions, filters, and actions for event-driven architectures. |
| Dead-Letter Queue | Automatic routing of undeliverable or failed messages to a secondary queue for inspection and reprocessing. |
| Scheduled Delivery | Schedule messages for future delivery at a specified time without requiring sender availability. |
| Transactions | ACID transaction support for grouping multiple operations across queues and topics into atomic units. |
| Auto-Forwarding | Automatically forward messages from one queue or subscription to another entity for chaining processing stages. |

## Use Cases

| Name | Description |
|------|-------------|
| Application Decoupling | Decouple microservices and distributed applications using asynchronous messaging for independent scaling and deployment. |
| Load Leveling | Buffer incoming requests during traffic spikes to protect backend services from overload. |
| Event-Driven Architecture | Build event-driven systems using publish-subscribe topics to broadcast events to multiple subscribers. |
| Workflow Orchestration | Coordinate multi-step business processes using message sessions and scheduled delivery for reliable workflow execution. |

## Integrations

| Name | Description |
|------|-------------|
| Azure Functions | Trigger serverless functions automatically when messages arrive in queues or topic subscriptions. |
| Azure Logic Apps | Build automated workflows that send and receive Service Bus messages with no-code connectors. |
| Azure Event Grid | Route Service Bus events to other Azure services for real-time event processing and monitoring. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Azure Service Bus Management API](openapi/azure-service-bus-openapi.yml)

### AsyncAPI

- [Azure Service Bus AsyncAPI](asyncapi/azure-service-bus-asyncapi.yml)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure Service Bus Management API](capabilities/shared/service-bus.yaml) — 6 operations for namespace, queue, and topic management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Messaging Management](capabilities/messaging-management.yaml) | Service Bus | 6 | Cloud Architect |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
