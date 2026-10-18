# Public Edge

Public Edge provides region-aware, capacity-aware and evidence-driven public
delivery for Kubernetes.

- Website: https://public-edge.github.io/website/
- Public roadmap: https://github.com/orgs/public-edge/projects
- Health authority: https://github.com/public-edge/public-edge-manager
- Egress fabric: https://github.com/public-edge/mihomos-cluster

GitHub is the coordination and event bus, not the runtime manager.

- Git and pull requests carry desired-state proposals and transitions.
- Kubernetes/K3s executes runtime state.
- Flux reconciles approved Git state.
- Headlamp provides lightweight runtime inspection.
- Prometheus, logs and traces remain in observability backends.
- GitHub Issues retain actionable events, decisions, evidence links and audit
  history, never bulk raw telemetry.

