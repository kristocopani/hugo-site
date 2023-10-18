---
# Generate the /admin/ page
type: wowchemycms
private: true
outputs:
  - wowchemycms_config
  - HTML
backend:
  name: git-gateway
  branch: master # Branch to update (optional; defaults to master)
---