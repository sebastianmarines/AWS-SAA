# AWS Solutions Architect Associate Notes

## EC2

## Instance types

- On demand
- Savings plans: Commitment to a consistent amount of usage in USD per hour
- Reserved: Commitment to a specific instance configuration
- Spot instances

Can attach a an Elastic Inference adapter to accelerate deep learning workloads.

A fleet contains the configuration information to launch a group of instances in a single API call.

Elastic Fabric adapter doesn't work in Windows instances.

## Cloudwatch Events

Uses the same underlying API as EventBridge, but EventBridge is preferred as it provides more features.
