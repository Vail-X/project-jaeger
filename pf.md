kubectl port-forward -n jaeger svc/jaeger-query 16686:16686
http://localhost:16686/search