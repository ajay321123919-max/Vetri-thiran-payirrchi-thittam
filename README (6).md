# 6. Project Testing

## Test Cases

| Test | User / Roles | Action | Expected Result |
|---|---|---|---|
| 01 | bb1 | Open list | EEE records viewable |
| 02 | No required role | Open list | Access denied |
| 03 | Admin | Open list | All records viewable |
| 04 | bb1 + bb2 | New | Create capability available |
| 05 | bb1 + bb2 + bb3 | Edit | Edit capability available |
| 06 | bb1 + bb2 + bb3 + bb4 | Delete | Delete capability available |

## Verification
Testing is performed through ServiceNow user impersonation.
