Istio is an open platform that provides a uniform way to connect, manage, and secure microservices. Istio supports managing traffic flows between microservices, enforcing access policies, and aggregating telemetry data, all without requiring changes to the microservice code


Istio Routing primitives - Gateway, VirtualService, DestinationRule

Flagger is a Kubernetes operator that automates the promotion of canary deployments using Istio, Linkerd, App Mesh, NGINX or Gloo routing for traffic shifting and Prometheus metrics for canary analysis.

https://github.com/weaveworks/flagger

What is Istio? (https://medium.com/namely-labs/a-crash-course-for-running-istio-1c6125930715)
Istio is a service mesh configuration engine. It reads the state of a Kubernetes cluster and performs updates to L7 (HTTP and gRPC) proxies that are initialized as “sidecars” to Kubernetes pods. These sidecars are Envoy containers that have been setup to read configuration from the Istio Pilot API (also a gRPC service) and then route traffic based on that configuration. The powerful L7 proxy under the hood allows us to leverage features such as metrics, tracing, retry logic, circuit breaking, load balancing and canary deployments.
