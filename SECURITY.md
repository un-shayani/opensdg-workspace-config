# Security Configuration

This workspace uses protected branch security:

- **Main branch is protected**: Only `@un-shayani` can approve changes
- **All role changes require PR**: Direct pushes to main are blocked
- **Code owner review required**: Changes to roles/ must be approved by owner
- **RSA signature validation**: All roles.json files are cryptographically signed

## Making Role Changes

1. Create a new branch from main
2. Make changes to roles.json
3. Create Pull Request to main branch
4. Owner review and approval required
5. PR merge updates the live configuration
