# Conditional alert template

Append to shared policy. Execute at [PRIVATE_ALERT_CADENCE]. See [worked example](examples/conditional-alert.synthetic.md); choose your own criteria and schedule privately.

Alert only when [PRIVATE_ALERT_CRITERIA] are met by a material new finding or status change. Distinguish confirmed from provisional evidence. Include a concise explanation, original source, uncertainty and recommended human validation. Route only through [AUTHORIZED_DELIVERY_SCOPE]. Do not execute remediation. Suppress duplicates where history permits. Handle collection failures according to [PRIVATE_COVERAGE_POLICY]; never imply silence proves safety.
