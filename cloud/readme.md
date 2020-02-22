## Catalog of patterns[](https://docs.microsoft.com/en-us/azure/architecture/patterns/#catalog-of-patterns)

| Pattern | Summary |
| --------|---------------|
| [Ambassador](https://docs.microsoft.com/en-us/azure/architecture/patterns/ambassador) | Create helper services that send network requests on behalf of a consumer service or application. |
| [Anti-Corruption Layer](https://docs.microsoft.com/en-us/azure/architecture/patterns/anti-corruption-layer) | Implement a façade or adapter layer between a modern application and a legacy system.
| [Asynchronous Request-Reply](https://docs.microsoft.com/en-us/azure/architecture/patterns/async-request-reply) | Decouple backend processing from a frontend host, where backend processing needs to be asynchronous, but the frontend still needs a clear response.
| [Backends for Frontends](https://docs.microsoft.com/en-us/azure/architecture/patterns/backends-for-frontends) | Create separate backend services to be consumed by specific frontend applications or interfaces.
| [Bulkhead](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead) | Isolate elements of an application into pools so that if one fails, the others will continue to function.
| [Cache-Aside](https://docs.microsoft.com/en-us/azure/architecture/patterns/cache-aside) | Load data on demand into a cache from a data store
| [Choreography](https://docs.microsoft.com/en-us/azure/architecture/patterns/choreography) | Let each service decide when and how a business operation is processed, instead of depending on a central orchestrator.
| [Circuit Breaker](https://docs.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker) | Handle faults that might take a variable amount of time to fix when connecting to a remote service or resource.
| [Claim Check](https://docs.microsoft.com/en-us/azure/architecture/patterns/claim-check) | Split a large message into a claim check and a payload to avoid overwhelming a message bus.
| [Compensating Transaction](https://docs.microsoft.com/en-us/azure/architecture/patterns/compensating-transaction)| Undo the work performed by a series of steps, which together define an eventually consistent operation.
| [Competing Consumers](https://docs.microsoft.com/en-us/azure/architecture/patterns/competing-consumers) | Enable multiple concurrent consumers to process messages received on the same messaging channel.
| [Compute Resource Consolidation](https://docs.microsoft.com/en-us/azure/architecture/patterns/compute-resource-consolidation) | Consolidate multiple tasks or operations into a single computational unit
| [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs) | Segregate operations that read data from operations that update data by using separate interfaces.
| [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing) | Use an append-only store to record the full series of events that describe actions taken on data in a domain.
| [External Configuration Store](https://docs.microsoft.com/en-us/azure/architecture/patterns/external-configuration-store) | Move configuration information out of the application deployment package to a centralized location.
| [Federated Identity](https://docs.microsoft.com/en-us/azure/architecture/patterns/federated-identity)  | Delegate authentication to an external identity provider.
| [Gatekeeper](https://docs.microsoft.com/en-us/azure/architecture/patterns/gatekeeper) | Protect applications and services by using a dedicated host instance that acts as a broker between clients and the application or service, validates and sanitizes requests, and passes requests and data between them.
| [Gateway Aggregation](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-aggregation) | Use a gateway to aggregate multiple individual requests into a single request.
| [Gateway Offloading](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-offloading) | Offload shared or specialized service functionality to a gateway proxy.
| [Gateway Routing](https://docs.microsoft.com/en-us/azure/architecture/patterns/gateway-routing) | Route requests to multiple services using a single endpoint.
| [Health Endpoint Monitoring](https://docs.microsoft.com/en-us/azure/architecture/patterns/health-endpoint-monitoring) | Implement functional checks in an application that external tools can access through exposed endpoints at regular intervals.
| [Index Table](https://docs.microsoft.com/en-us/azure/architecture/patterns/index-table) | Create indexes over the fields in data stores that are frequently referenced by queries.
| [Leader Election](https://docs.microsoft.com/en-us/azure/architecture/patterns/leader-election) | Coordinate the actions performed by a collection of collaborating task instances in a distributed application by electing one instance as the leader that assumes responsibility for managing the other instances.
| [Materialized View](https://docs.microsoft.com/en-us/azure/architecture/patterns/materialized-view) | Generate prepopulated views over the data in one or more data stores when the data isn't ideally formatted for required query operations.
| [Pipes and Filters](https://docs.microsoft.com/en-us/azure/architecture/patterns/pipes-and-filters) | Break down a task that performs complex processing into a series of separate elements that can be reused.
| [Priority Queue](https://docs.microsoft.com/en-us/azure/architecture/patterns/priority-queue) | Prioritize requests sent to services so that requests with a higher priority are received and processed more quickly than those with a lower priority.
| [Publisher/Subscriber](https://docs.microsoft.com/en-us/azure/architecture/patterns/publisher-subscriber) | Enable an application to announce events to multiple interested consumers asynchronously, without coupling the senders to the receivers.
| [Queue-Based Load Leveling](https://docs.microsoft.com/en-us/azure/architecture/patterns/queue-based-load-leveling) | Use a queue that acts as a buffer between a task and a service that it invokes in order to smooth intermittent heavy loads.
| [Retry](https://docs.microsoft.com/en-us/azure/architecture/patterns/retry) | Enable an application to handle anticipated, temporary failures when it tries to connect to a service or network resource by transparently retrying an operation that's previously failed.
| [Scheduler Agent Supervisor](https://docs.microsoft.com/en-us/azure/architecture/patterns/scheduler-agent-supervisor) | Coordinate a set of actions across a distributed set of services and other remote resources.
| [Sequential Convoy](https://docs.microsoft.com/en-us/azure/architecture/patterns/sequential-convoy) | Process a set of related messages in a defined order, without blocking processing of other groups of messages.
| [Sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding) | Divide a data store into a set of horizontal partitions or shards.
| [Sidecar](https://docs.microsoft.com/en-us/azure/architecture/patterns/sidecar) | Deploy components of an application into a separate process or container to provide isolation and encapsulation.
| [Static Content Hosting](https://docs.microsoft.com/en-us/azure/architecture/patterns/static-content-hosting) | Deploy static content to a cloud-based storage service that can deliver them directly to the client.
| [Strangler](https://docs.microsoft.com/en-us/azure/architecture/patterns/strangler) | Incrementally migrate a legacy system by gradually replacing specific pieces of functionality with new applications and services.
| [Throttling](https://docs.microsoft.com/en-us/azure/architecture/patterns/throttling) | Control the consumption of resources used by an instance of an application, an individual tenant, or an entire service.
| [Valet Key](https://docs.microsoft.com/en-us/azure/architecture/patterns/valet-key) | Use a token or key that provides clients with restricted direct access to a specific resource or service.
