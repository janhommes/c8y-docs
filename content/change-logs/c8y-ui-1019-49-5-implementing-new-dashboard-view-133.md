---
date: ""
title: Implementing new dashboard view (#133)
product_area: Application enablement & solutions
change_type:
  - value: change-2c7RdTdXo4
    label: feat
component:
  - value: component--KIsStyzM
    label: Cockpit
build_artifact:
  - value: tc-pjJiURv9Y
    label: c8y-ui
ticket: MTM-12345
version: 1019.49.5
---
- the dashboard editing was changed. You now need to first hit edit, before you can edit a dashboard
 -  Changes while editing can now be redo or undo
 - Dashboard changes are stored in a history and can be reset
 - Typed dashboards (dashboard that are applied to the same device type) can now easier be activated or deactivated and there are more visible information, indicating that and how a typed dashboard is used.
 - Asset can also use now typed based dashboards if a flag is activated (by default deactivated).