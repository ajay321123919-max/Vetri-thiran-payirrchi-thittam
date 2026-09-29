# 5. Project Development

## Custom Table
Table: `u_institution_details`

## READ ACL
- Type: record
- Operation: read
- Name: `u_institution_details`
- Required role: `bb1`
- Data condition: Branch is EEE
- Advanced: true

## Script
```javascript
(function () {
  if (gs.hasRole('admin')) {
    return true;
  }

  if (gs.hasRole('bb1')) {
    return true;
  }

  return false;
})();
```

## Other ACLs
- CREATE → `bb2`
- WRITE → `bb3`
- DELETE → `bb4`
