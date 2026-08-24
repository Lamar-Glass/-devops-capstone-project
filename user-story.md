# User Story Template

```markdown
## As a [type of user], I want [goal] so that [reason].

### Description
[Short description of the feature or need]

### Acceptance Criteria
- [ ] Given [context] when [action] then [result]
- [ ] Given [context] when [action] then [result]

### Notes
[Any additional notes, dependencies, or constraints]

### Story Points
[S | 3 points | M | 5 points | L | 8 points | XL | 13 points]
```

## Example

```markdown
## As a site member, I want to be able to reset my password so that I can regain access to my account if I forget my credentials.

### Description
Customers who forget their password need a self-service way to reset it securely
without contacting support.

### Acceptance Criteria
- [ ] Given I am on the login page when I click "Forgot password" then I am prompted for my email address
- [ ] Given I submitted my email address when the email exists then I receive a password reset link
- [ ] Given I clicked the reset link and set a new password when I log in with the new password then access is granted

### Notes
Reset links must expire after 24 hours.

### Story Points
M — 5 points
```
