---
title: SNFR8 - Module Owner(s) GitHub
url: /spec/SNFR8
geekdocNav: true
geekdocAlign: left
geekdocAnchor: true
type: posts
tags: [
  Class-Resource, # MULTIPLE VALUES: this can be "Class-Resource" AND/OR "Class-Pattern" AND/OR "Class-Utility"
  Class-Pattern, # MULTIPLE VALUES: this can be "Class-Resource" AND/OR "Class-Pattern" AND/OR "Class-Utility"
  Type-NonFunctional, # SINGLE VALUE: this can be "Type-Functional" OR "Type-NonFunctional"
  Category-Contribution/Support, # SINGLE VALUE: this can be "Category-Testing" OR "Category-Telemetry" OR "Category-Contribution/Support" OR "Category-Documentation" OR "Category-CodeStyle" OR "Category-Naming/Composition" OR "Category-Inputs/Outputs" OR "Category-Release/Publishing"
  Language-Bicep, # MULTIPLE VALUES: this can be "Language-Bicep" AND/OR "Language-Terraform"
  Language-Terraform, # MULTIPLE VALUES: this can be "Language-Bicep" AND/OR "Language-Terraform"
  Severity-MUST, # SINGLE VALUE: this can be "Severity-MUST" OR "Severity-SHOULD" OR "Severity-MAY"
  Persona-Owner, # MULTIPLE VALUES: this can be "Persona-Owner" AND/OR "Persona-Contributor"
  Lifecycle-Initial, # SINGLE VALUE: this can be "Lifecycle-Initial" OR "Lifecycle-BAU" OR "Lifecycle-EOL"
  Validation-TBD # SINGLE VALUE: this can be "Validation-Manual" OR "Validation-CI/Informational" OR "CI/Enforced"
]
priority: 1100
---

#### ID: SNFR8 - Category: Contribution/Support - Module Owner(s) GitHub

A module **MUST** have an owner that is defined and managed by a GitHub Team in the Azure GitHub organization.

Today this is only Microsoft FTEs, but everyone is welcome to contribute. The module just **MUST** be owned by a Microsoft FTE (today) so we can enforce and provide the long-term support required by this initiative.

{{< hint type=note >}}

The names for the GitHub teams for each approved module are already defined in the respective [Module Indexes](/Azure-Verified-Modules/indexes/). These teams **MUST** be created (and used) for each module.

{{< /hint >}}