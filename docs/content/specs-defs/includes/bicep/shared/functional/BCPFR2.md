---
title: BCPFR2 - Role Assignments Role Definition Mapping
url: /spec/BCPFR2
geekdocNav: true
geekdocAlign: left
geekdocAnchor: true
type: posts
tags: [
  Class-Resource, # MULTIPLE VALUES: this can be "Class-Resource" AND/OR "Class-Pattern" AND/OR "Class-Utility"
  Class-Pattern, # MULTIPLE VALUES: this can be "Class-Resource" AND/OR "Class-Pattern" AND/OR "Class-Utility"
  Type-Functional, # SINGLE VALUE: this can be "Type-Functional" OR "Type-NonFunctional"
  Category-Naming/Composition, # SINGLE VALUE: this can be "Category-Testing" OR "Category-Telemetry" OR "Category-Contribution/Support" OR "Category-Documentation" OR "Category-CodeStyle" OR "Category-Naming/Composition" OR "Category-Inputs/Outputs" OR "Category-Release/Publishing"
  Language-Bicep, # MULTIPLE VALUES: this can be "Language-Bicep" AND/OR "Language-Terraform"
  Severity-MUST, # SINGLE VALUE: this can be "Severity-MUST" OR "Severity-SHOULD" OR "Severity-MAY"
  Persona-Owner, # MULTIPLE VALUES: this can be "Persona-Owner" AND/OR "Persona-Contributor"
  Persona-Contributor, # MULTIPLE VALUES: this can be "Persona-Owner" AND/OR "Persona-Contributor"
  Lifecycle-BAU, # SINGLE VALUE: this can be "Lifecycle-Initial" OR "Lifecycle-BAU" OR "Lifecycle-EOL"
  Validation-TBD # SINGLE VALUE: this can be "Validation-Manual" OR "Validation-CI/Informational" OR "CI/Enforced"
]
priority: 10020
---

#### ID: BCPFR2 - Category: Composition - Role Assignments Role Definition Mapping

Module owners **MAY** define common RBAC Role Definition names and IDs within a variable to allow consumers to define a RBAC Role Definition by their name rather than their ID, this should be self contained within the module themselves.

However, they **MUST** use only the official RBAC Role Definition name within the variable and nothing else.

To meet the requirements of [BCPFR2](/Azure-Verified-Modules/spec/BCPFR2), [BCPNFR5](/Azure-Verified-Modules/spec/BCPNFR5) and [BCPNFR6](/Azure-Verified-Modules/spec/BCPNFR6) you **MUST** use the below code sample in your AVM Modules to achieve this.

{{< include file="/static/includes/sample.rbacMapping.bicep" language="bicep" options="linenos=false" >}}