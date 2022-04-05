# AZ-400: Develop a Site Reliability Engineering (SRE) strategy (5-10%)

## Develop an actionable alerting strategy
- Identify and recommend metrics on which to base alerts
- Implement alerts using appropriate metrics
- Implement alerts based on appropriate log messages
- Implement alerts based on application health checks
- Analyze combinations of metrics
- Develop communication mechanism to notify users of degraded systems
- Implement alerts for self-healing activities
    - scaling
    - failovers

## Design a failure prediction strategy
- Analyze behavior of system with regards to load and failure conditions
- Calculate when a system will fail under various conditions
- Measure baseline metrics for system
- Leverage Application Insights Smart Detection and Dynamic thresholds in Azure Monitor

## Design and implement a health check
- Analyze system dependencies to determine which dependency should be included in health check
- Calculate healthy response timeouts based on SLO for the service
- Design approach for partial health situations
- Design approach for piecemeal recovery
    - to improve recovery time objective strategies
- Integrate health check with compute environment
- Implement different types of health checks
    - container liveness
    - startup
    - shutdown

[Return to Table of Contents](README.md)