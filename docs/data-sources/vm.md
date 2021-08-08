---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "truenas_vm Data Source - terraform-provider-truenas"
subcategory: ""
description: |-
  
---

# truenas_vm (Data Source)



## Example Usage

```terraform
data "truenas_vm" "vm" {
  id = "3"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **id** (String) VM ID

### Read-Only

- **autostart** (Boolean) `true` if VM is set to autostart
- **description** (String) VM description
- **device** (Set of Object) (see [below for nested schema](#nestedatt--device))
- **memory** (Number) Total memory available for VM (bytes)
- **name** (String) VM name
- **vcpus** (Number) Number of virtual CPUs

<a id="nestedatt--device"></a>
### Nested Schema for `device`

Read-Only:

- **attributes** (Map of String)
- **id** (String)
- **order** (Number)
- **type** (String)

