In the `envoy` go-control-plane xDS server, use a separate snapshot cache for Endpoints, to minimize the amount of unnecessary xDS traffic generated.