# Concurrency Rules

- Prefer structured concurrency.
- Use async/await where appropriate.
- Keep UI state changes on MainActor.
- Avoid detached tasks unless there is a concrete reason.
- Consider task cancellation.
- Avoid data races and unsafe shared mutable state.
- Do not use concurrency merely for complexity; use the simplest correct model.
