---
name: "Modify Organization"
about: "Use this template tomodify the NPU resources configured for an organization"
title: "Revise ORGANIZATION"
labels: "npu-resources"
assignees: ""
---

Welcome to use this template to submit an issue to revise your organization to the NPU Runners. Please follow the instructions below to fill in the relevant information so that we can process your request more efficiently.

```yaml
org-name: 
github-app: 
  instalation-id: 
runner-group: 
  group-name: 
runner-set: 
  npu-counts: 
```

| Field | Description | Example | Required |
|------|------|------|-----|
| `org-name` | Full name of the organization | `awesome-ai-org` | ✅ |
| `github-app.installation-id` | Installation ID after installing ascend-runner-mgmt | `11111111` | ✅ |
| `runner-group.group-name` | The group name of the configured runner group | `ascend-ci` | ✅ |
| `runner-set.npu-counts` | The number array of NPU chip | `1,2` | ✅ |
