# Identity and Access

Who is the User, how can they access a Business and what can he do?

## User

- Name
- Email
- Password
- Phone (optional)
- Role (in a business)

## Business

- Business Name
- CNPJ
- Address(es)

## Role

- Permissions

## Business Rules

- Email must be globally unique among Users.
- CNPJ must be globally unique among Businesses.
- A Business can have a maximum of 10 addresses.
- To access the Marketplace, the user must be associated with a Business.
- A User can create a Business and is automatically associated with it.
- To join an existing Business,the User must receive an invitation from a Business Member with permission to manage Business Members.
- A User can join more than one Business
- Every action requires a Permission.
- To have Permissions, a user must have a Role
- A Role can have multiple Permissions.
