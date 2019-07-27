## Architecture Style
* N-Tier
    * layered
    * Web => Business => Data
    * Easy to Understand
    * Difficult to change
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier)
    * Closed layer (Calls only one layer below it)
    * Open layer (Can call any layer below it)
* Web-Queue-Worker 
    * Front end for HTTP and backend for CPU intensive
    * Front end communicates to banckend through queue.
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/web-queue-worker)

* Microservices
    * Composed of many small independent services
    * Each service has small business functionality.
    * Services are loosely coupled , communicated through API contracts.
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/microservices)

* Event driven architecture
    * pub-sub model
    * producers and consumers are independent
    * applications that process large volume of data with low latency
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven)

* Big Data
    * Big data divides a very large dataset into chunks, performing parallel processing across the entire set, for analysis and reporting
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/big-data)
* Big Compute
    * high-performance computing (HPC), makes parallel computations across a large number (thousands) of cores.
    * Domains include simulations, modeling, and 3-D rendering.
    * [source](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/big-compute)