### Example 1: Code snippet

```powershellImport-Module Microsoft.Graph.Beta.Calendar

# A UPN can also be used as -UserId.
Remove-MgBetaUserEvent -UserId $userId -EventId $eventId
```
This example shows how to use the Remove-MgBetaUserEvent Cmdlet.
To learn about permissions for this resource, see the [permissions reference](/graph/permissions-reference).

