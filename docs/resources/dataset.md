---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "truenas_dataset Resource - terraform-provider-truenas"
subcategory: ""
description: |-
  
---

# truenas_dataset (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String)
- **pool** (String)

### Optional

- **acl_mode** (String) Determine how chmod behaves when adjusting file ACLs. See the zfs(8) aclmode property.
- **atime** (String) Choose 'on' to update the access time for files when they are read. Choose 'off' to prevent producing log traffic when reading files
- **case_sensitivity** (String)
- **comments** (String)
- **compression** (String)
- **copies** (Number)
- **deduplication** (String)
- **encrypted** (Boolean)
- **encryption_algorithm** (String)
- **encryption_key** (String, Sensitive)
- **exec** (String)
- **generate_key** (Boolean)
- **inherit_encryption** (Boolean)
- **parent** (String)
- **passphrase** (String, Sensitive)
- **pbkdf2iters** (Number)
- **quota_bytes** (Number)
- **quota_critical** (Number)
- **quota_warning** (Number)
- **readonly** (String)
- **record_size** (String)
- **ref_quota_bytes** (Number)
- **ref_quota_critical** (Number)
- **ref_quota_warning** (Number)
- **share_type** (String)
- **snap_dir** (String)
- **sync** (String) 'standard' uses the sync settings that have been requested by the client software, 'always' waits for data writes to complete, and 'disabled' never waits for writes to complete.
- **timeouts** (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))

### Read-Only

- **acl_type** (String)
- **id** (String) The ID of this resource.
- **managed_by** (String)
- **mount_point** (String)

<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- **create** (String)
- **delete** (String)
- **update** (String)

