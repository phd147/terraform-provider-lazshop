---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "qernal_project Resource - qernal"
subcategory: ""
description: |-
  
---

# qernal_project (Resource)



## Example Usage

```terraform
# Manage example qernal_project.
resource "qernal_project" "example" {
  name   = "example project name"
  org_id = "00000000-0000-0000-0000-000000000000"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `name` (String)
- `org_id` (String)

### Read-Only

- `date` (Attributes) (see [below for nested schema](#nestedatt--date))
- `id` (String) The ID of this resource.

<a id="nestedatt--date"></a>
### Nested Schema for `date`

Read-Only:

- `created_at` (String)
- `updated_at` (String)
