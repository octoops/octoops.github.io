# Most useful open source DevOps tools.

## Docker

In 2006 Google introduced cgroups, allowing you take a process, isolate it, and limit its resources. In 2008 came lxc, with the additional functionality of kernel module. This allowed name spacing and limiting what a process can see.

In 2013 Docker was released: it can do all the above, and additionally pipeline and tooling to build the images that spawn to the containers, and control map ports.

Docker is performing containerization - operating-system-level virtualization. It is the most popular container runtime on the market right now and a central component of Kubernetes.
Ops Tools Written in Go

## Kubernetes

Borg was created in Google in 2003 as a cluster manager with the purpose to efficiently schedule runs hundreds of thousands of jobs and makes computing much more efficient. It was written in C++.

In 2014 Kubernetes was released as the OS equivalent: a container orchestrator used in production by large companies to run distributed services.

Kubernetes is a system for automating deployment, scaling, and management of containerized applications. It groups containers, that make up an application into logical units, for easy management and discovery. Kubernetes can scale and add infinite amount of resources without increasing the ops team. It runs on on-premises, hybrid, or public cloud infrastructure.

## Helm

Helm is the package manager for Kubernetes. It is the best way to find, share, and use software built for Kubernetes. Helm Charts help define, install, and upgrade complex Kubernetes application; version control, share, and publish config files instead of getting lost in copy-paste.

## Terraform

Terraform is an open-source infrastructure as code software tool that provides a consistent CLI workflow to manage hundreds of cloud services. Terraform codifies cloud APIs into declarative configuration files.

## Prometheus

Borg Mon was also develop in 2003 as an internal monitoring system complimentary for Borg, and it was also written in C++.

In 2012 Prometheus was incepted as an open source equivalent: a time-series data as a data source, for collecting metrics and generating alerts.

The time series are identified by a metric name and a set of key-value pairs, which makes powerful queries and efficient storage, built-in alerting, it’s supporting 10 languages and bridges data import from sources like Docker and StatsD.

## Grafana

Grafana is a time series analytics and monitoring and visulatization platform. Some of the officially supported datasources are: Prometheus, InfluxDB and Elasticsearch. Each Data Source has a query editor customized for its features and capabilities. Each Data Source is tied to a panel, and all the panels together make a dashboard where the time period can be controlled, and the annotations display event data across the panels for correlating the time series data with other events.

## Etcd

Chubby was created in 2006 as a distributed lock manager. Fun fact: the SLO was 99.99 (4 nines) and to make sure it is met - the team often had to carry out a planned outage for up to 13 min per quarter!

In 2013 etcd was developed: a strongly consistent distributed key value store, into which you can read and write data, that provides a reliable way to store data across a cluster of machines.

Etcd is a central component of Kubernetes and it’s used in mission critical distributed systems, because it gracefully handles leader elections during network partitions and tolerates machine failure, including the leader. A simple use-case is to store db connection details in etcd as key value pairs. These values can be watched, allowing your app to reconfigure itself when they change. Now also a CNCF project!

## The Open Tracing Project

Distributed tracing anyone? Used for profiling and monitoring applications on distributed software architectures, such as microservices, distributed tracing helps debugging complex systems by pinpointing where failures occurs and optimizing by spotting what causes poor performance.

The OpenTracing API Project is working towards creating more standardized APIs and instrumentation, and it’s comprised of an API specification, frameworks and libraries that have implemented the specification, and documentation for the project. It allows developers to add instrumentation to the code using APIs that do not lock them into any one particular product or vendor.

## Jaeger

Open Tracing compatible, Jaeger is an end-to-end distributed tracing for monitoring and troubleshooting transactions in complex distributed systems that many time ground in networking or observability.

Jaeger is a tool for distributed transaction monitoring and context propagation, performance and latency optimization, root cause analysis and service dependency analysis.

## Istio

A service mesh that is a configurable infrastructure layer, for a microservices architecture. Istio makes communication between service instances flexible, reliable, fast and secure. It’s added to the application by deploying a sidecar (a proxy) next to each service, which means no code changes are needed!

This allows automatic discovery of devices and services, tracing, monitoring, logging, observability into the platform, security by means like access control and authentication, access policy control and traffic control.

## CNCF

The Cloud Native Computing Foundation is a home to many of the above projects. It is an open source software foundation dedicated to making cloud native computing universal and sustainable. The foundation builds sustainable ecosystems and fosters a community around a constellation of high-quality open source projects that orchestrate containers as part of a microservices architecture.

Cloud native computing uses an open source software stack to deploy applications as microservices packaging each part into its own container, and dynamically orchestrating those containers to optimize resource utilization.