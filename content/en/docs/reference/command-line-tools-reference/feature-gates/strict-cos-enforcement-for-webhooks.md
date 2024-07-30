---
title: StrictCostEnforcementForWebhooks
content_type: feature_gate
_build:
  list: never
  render: false

stages:
  - stage: alpha
    defaultValue: false
    fromVersion: "1.31"
    
---
Enable the enforcement of the strict cost calculation for CEL extended libraries in `matchConditions` field under Webhooks.
