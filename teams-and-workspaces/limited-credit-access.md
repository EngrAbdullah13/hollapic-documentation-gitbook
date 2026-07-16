# Limited credit access

Limited credit access reserves a protected allocation for one collaborator.

## Behavior

The collaborator can spend only their remaining allocation. Owners, full-credit collaborators, and other limited collaborators cannot spend that reserved allocation.

## Formula

```text
free/shared credits =
owner total remaining credits
- sum of every active or pending Limited Credit collaborator's unused reserved credits
```

## Related guides

- [Set collaborator credit limits](collaborator-credit-limits.md)
- [Workspace credit problems](../troubleshooting/workspace-credit-problems.md)
