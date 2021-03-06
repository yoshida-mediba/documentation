---
title: Datadog-Pingdom Integration
integration_title: Pingdom
kind: integration
git_integration_title: pingdom
---

### Overview
{: #int-overview}

Track Pingdom downtime events and user-centric performance metrics in Datadog, for correlation with other relevant events and metrics.

At this time we track the response_time metric for any sites you configure on the Pingdom website.

*Note: Events and metrics can only be imported for Pingdom customers at the Starter level or above.*

## Metrics

<%= get_metrics_from_git() %>

### Questions and Troubleshooting

**Q:** Does Datadog support transaction checks?

**A:** Pingdom does not provide an API for transaction checks, so we’re not able to show them in Datadog. The transaction monitor feature was in beta until recently, so if it becomes available we will look to support it.
