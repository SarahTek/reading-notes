# Reading: Access Control (ACL)

## 5 steps to RBAC

1. What is Role Based Access Control (RBAC) and why do we care?

- RBAC is the idea of assigning system access to users based on their role within an organization. It improves overall security as it relates to compliance, confidentiality, privacy, and access management to resources and other sensitive data and systems.

2. Describe a Role/Permission heirarchy that you might implement using RBAC.

- user can only read.
- Author: has access to publish their own posts
- Contributor: can write their own posts, but can’t publish
- Editor: has access to publish and edit posts, including those of other users
- Administrator: has access to the administrative capabilities
- Super Admin: has all of the access of the other roles as well as site administration capabilities

3. What approach might you take to implement RBAC?

- inventory your system
- analyze your workforce and create roles
- assign people to roles
- never make one-off changes
- audit : Periodically review your roles, the employees assigned to them, and the access permitted for each 

## wiki - RBAC

1. If Authentication is “you are who you say you are,” what is Authorization?

- Authorization is the process of giving someone the ability to access a resource.

2. Name three primary rules defined for RBAC.

- Role assignment: A subject can exercise a permission only if the subject has selected or been assigned a role.
- Role authorization: A subject's active role must be authorized for the subject. With rule 1 above, this rule ensures that users can take on only roles for which they are authorized.
- Permission authorization: A subject can exercise a permission only if the permission is authorized for the subject's active role. With rules 1 and 2, this rule ensures that users can exercise only permissions for which they are authorized.

3. Describe RBAC to a non-technical friend.

## RBAC tutorial

1. What Are access rights Associated with? The User? or The Role? Explain.

- `rights` are for being able to acces a certain resources and they are associated with the `role` not the `user`
- what roles do I have on my system and for each role what kinds of resources do they need to have the acces to.

2. Access Rights, or Authorization, is activated after a user successfully does what?

- if the user sucessfully Login / authenticate themselves to the system and then user can activate a role or more role for themselves and based on that they will decide what the user can have access to.

3. Explain how RBAC might benefit a business.

- policy does not need to change/ update when a person with a role leaves the organizing. because policy is associated wirh role not with the person/user.
- when new employee comes we decide what role is appropriate for them and assign a role then they will have access rights to the resources
- Revisiting least privilege: this is very useful for damage containment in case if something happens you dont negatively impact resources.
- SELinux supprts RBAC

## Resources

- [5 steps to RBAC](https://www.csoonline.com/article/3060780/5-steps-to-simple-role-based-access-control.html)

- [wiki - RBAC](https://en.wikipedia.org/wiki/Role-based_access_control)

- [RBAC tutorial](https://www.youtube.com/watch?v=C4NP8Eon3cA)
