# Deployment guide

1. Select a managed assistant with supported scheduled execution and public information retrieval. Confirm actual permissions and product capabilities.
2. Read the [worked examples](../config/examples/README.md) and [personalization guide](personalization-guide.md). Copy the empty templates in config/ to a private location. Define relevant categories, sources, escalation criteria and schedules; never commit real configuration here.
3. Optionally configure a managed feed delivery service and a dedicated public-intelligence message folder. Test routing and read-only scoped retrieval. Do not forward confidential messages.
4. Combine the [shared prompt](../prompts/shared-policy.md) with the [conditional alert](../prompts/conditional-alert.md) for one task, and with the [periodic digest](../prompts/periodic-digest.md) for another. Substitute placeholders privately. The [worked prompt examples](../prompts/examples/README.md) demonstrate how to translate descriptive configuration into instructions manually; no automatic YAML binding is provided.
5. Execute the validation plan with synthetic inputs before relying on outputs. Test scheduled execution separately from interactive execution.
6. Review observed coverage, freshness and evidence quality before expanding scope.

No local runtime is required by this conceptual design if the selected managed services provide the required capabilities. Costs, quotas, features and availability depend on the provider. This guide is not an automated installer.
