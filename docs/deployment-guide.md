# Deployment guide

1. Select a managed assistant with supported scheduled execution and public information retrieval. Confirm actual permissions and product capabilities.
2. Privately define relevant asset categories, trusted sources, escalation criteria and schedules. Copy the example configuration into a private location; never commit populated configuration here.
3. Optionally configure a managed feed delivery service and a dedicated public-intelligence message folder. Test routing and read-only scoped retrieval. Do not forward confidential messages.
4. Combine the shared prompt with the conditional alert prompt for one task, and with the periodic digest prompt for another. Substitute placeholders privately. Confirm actual scheduling and connector support.
5. Execute the validation plan with synthetic inputs before relying on outputs. Test scheduled execution separately from interactive execution.
6. Review observed coverage, freshness and evidence quality before expanding scope.

No local runtime is required by this conceptual design if the selected managed services provide the required capabilities. Costs, quotas, features and availability depend on the provider. This guide is not an automated installer.
